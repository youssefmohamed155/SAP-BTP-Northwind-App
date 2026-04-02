# Project Title
## SAP BTP Northwind Fiori Application

## Description
This project is a SAP Fiori application developed using SAP Business Technology Platform (BTP).  
It connects to the Northwind OData service to retrieve product data and display it using a Fiori List Report interface.

---

## Architecture Overview
The application is built using SAP Business Application Studio and deployed on Cloud Foundry within SAP BTP.  
The Destination service is used to connect the application to the external Northwind OData service.  
Cloud Foundry hosts and runs the application, while the destination handles secure communication between the app and the external service.

---

## Setup Instructions
1. Create an SAP BTP Trial Account  
2. Create a Subaccount and enable Cloud Foundry environment  
3. Create a Cloud Foundry space (e.g., dev)  
4. Subscribe to required services:
   - Business Application Studio  
   - Destination Service  
5. Configure a destination to connect to the Northwind OData service  
6. Open SAP Business Application Studio and create a Fiori Dev Space  
7. Use SAP Fiori Application Generator to create a new app  
8. Connect the app to the Northwind OData service  
9. Run and test the application  

---

## OData Entity Used
The **Products** entity set was used from the Northwind OData service.  
It was selected because it provides structured product data such as name, price, and category, which is ideal for displaying in a List Report interface.

---

## Challenges Faced
One of the main challenges was configuring the destination correctly to connect to the Northwind OData service.  
Initially, the application could not retrieve data due to incorrect configuration.  
This issue was resolved by verifying the destination URL and ensuring the correct connection type and settings were applied.

---

## Bonus Tasks Completed
No bonus tasks were completed.

---

## Deployed Application URL
Not available.

---

## Screenshots

### SAP BTP Setup
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/SAP%20BTP%20Global%20Account.png)
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/Create%20a%20Cloud%20Foundry%20Space%20named%20dev.png)

### Subscribed Services
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/Subscribed%20Services.png)

### Destination Configuration
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/Destination%20Configuration.png)

### SAP Business Application Studio
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/SAP%20Business%20Application%20Studio%20Dev%20Space.png)

### Fiori Application Generator
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/SAP%20Fiori%20Application%20Generator.png)

### Running Application
![Model](https://github.com/youssefmohamed155/SAP-BTP-Northwind-App/blob/main/SAP%20Fiori%20Application%20Running.png)

---

## Author
Youssef Mohammed  
Software Engineer
