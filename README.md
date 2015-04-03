## **Common consent and your web application**

### **What is common consent?**

Common consent is Microsoft's framework for providing OAuth for both 1st and 3rd party applications. This framework allows users to create applications and define a permission model for these application around OAuth.

There are two types of applications that can take advantage of the common consent framework. The first type of applications are known as _client applications_. Client applications are apps that consume that consume the APIs of other applications. Microsoft's common consent framework allows client applications to leverage the full suite of Microsoft's Office 365 APIs, as well as the APIs of any published 3rd party application. The second type of applications are known as _resource applications_. Resource applications are apps that provide APIs to other applications. Microsoft's Office 365 APIs are examples of resource applications. A developer can create resource applications and define a rich OAuth permission model for these apps using the common consent framework. 

**What do I get out of it?**

Identity management is a top priority for many app developers today. The common consent model aims to provide cloud backed identity management for your app. By defining a framework to provide OAuth to applications, Microsoft's common consent framework makes it easy to for your application to sign in users, request permissions to resource apps like Exchange, and even request tokens for actions such as getting a user's calendar events. Furthermore, this makes it easy for web API developers to define their own permission model, securing their web APIs with Microsoft's enterprise grade security.

**Why is this important?**

Currently, there are numerous cloud based identity management models offered by numerous services. Facebook, Google and Amazon are among dozens of providers who are building a model to support OAuth for developers. However, the common consent framework allows developers more flexibility in not only consuming resource APIs, but also defining resource APIs to be leveraged by other applications.

### **Scenarios**

* Providing single sign on
* Reading mail from Exchange and sites from Sharepoint
* Providing "Data.Read" claim for my own resource application

### **Deeper dive**

* Defining App roles
* Admin vs User level consent
* Extending consent permissions for individual tenants
