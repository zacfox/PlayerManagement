# PlayerManagement
Universelle Spielerverwaltung für verschiedene Games

---

Das Projekt dient dazu, Personen (Spieler) in einer SQL Datenbank zu verwalten.
Das Frontend besteht aus einer Single-Page-Application

Dazu gehören die Projekte: 
  - https://github.com/zacfox/PlayerManagementEJB
  - https://github.com/zacfox/PlayerManagementWeb

---

###Folgende Technologien kommen zu Einsatz:
* Website
  * HTML -> Bootstrap
  * JavaScript -> JQuery, AngularJS
  
* Data-Layer (Managed Beans)
  * CDI
  * EJB
  
* Persintenz
  * JPA (wird vom Data-Layer angesteuert)
  
* RESTful Service
  * JAX-RS (ermöglicht den Clients Zugriff auf die Data-Layer)
  
* WebSockets
  * für die beidseitige Kommunikation mit dem Browser
  
* WildFly
  * als Java Application Server
