---
title: "IsLessThanOrEqualTo"
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- IsLessThanOrEqualTo
api_type:
- schema
ms.assetid: b5d85eb2-5e15-4d01-ad49-6289e735ad8a
description: "The IsLessThanOrEqualTo element represents a search expression that compares a property with either a constant value or another property and returns true if the first property is less than or equal to the second."
---

# IsLessThanOrEqualTo

The **IsLessThanOrEqualTo** element represents a search expression that compares a property with either a constant value or another property and returns **true** if the first property is less than or equal to the second. 
  
```xml
<IsLessThanOrEqualTo>
   <FieldURI/>
   <FieldURIOrConstant/>
</IsLessThanOrEqualTo>
```

```xml
<IsLessThanOrEqualTo>
   <IndexedFieldURI/> 
   <FieldURIOrConstant/>
</IsLessThanOrEqualTo>
```

```xml
<IsLessThanOrEqualTo>
   <ExtendedFieldURI/> 
   <FieldURIOrConstant/>
</IsLessThanOrEqualTo>
```

**IsLessThanOrEqualToType**

## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

|**Element**|**Description**|
|:-----|:-----|
|[FieldURI](fielduri.md) <br/> |Identifies frequently referenced properties by URI.  <br/> |
|[IndexedFieldURI](indexedfielduri.md) <br/> |Identifies individual members of a dictionary.  <br/> |
|[ExtendedFieldURI](extendedfielduri.md) <br/> |Identifies MAPI properties.  <br/> |
|[FieldURIOrConstant](fielduriorconstant.md) <br/> |Represents either a property or a constant value to be used when comparing with another property.  <br/> |
   
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[Restriction](restriction.md) <br/> |Represents the restriction or query that is used to filter items or folders in FindItem/FindFolder and search folder operations.  <br/> |
|[Not](not.md) <br/> |Represents a search expression that negates the Boolean value of the search expression it contains.  <br/> |
|[And](and.md) <br/> |Represents a search expression that enables you to perform a Boolean And operation between two or more search expressions. The result of the And operation is **true** if all of the search expressions contained within the And are **true**.  <br/> |
|[Or](or.md) <br/> |Represents a search expression that performs a logical OR on the search expression it contains. [Or](or.md) will return **true** if any of its children return true. [Or](or.md) must have two or more children.  <br/> |
   
## Remarks

The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema Name  <br/> |Types schema  <br/> |
|Validation File  <br/> |Types.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also

- [EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)

