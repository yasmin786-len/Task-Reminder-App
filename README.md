# Java-Based Task Reminder Application  
## Using Timers, Collections, JDBC & Spring Boot REST APIs

---

## 📌 Project Overview

This project is a **Java-based Task Reminder Application** designed to help users manage tasks efficiently through scheduling, reminders, tracking, and reporting. It leverages **core Java concepts** such as collections, concurrency, and timers, along with **Spring Boot** for building secure and scalable RESTful APIs.

The application allows users to add tasks, set due dates, receive reminders via email, track completion status, and generate task overviews that can be exported as CSV files. It focuses on productivity and reliability **without using AI or heavy frameworks beyond Spring Boot**.

---

## 🎯 Key Outcomes

- Reliable task scheduling with timely reminders using Java concurrency  
- Accurate tracking of completed and pending tasks via database persistence  
- Comprehensive task reports and overviews exportable as CSV files  
- Improved productivity through secure data handling, email alerts, and API-driven access  

---

## 🧩 Modules Implemented

### 1️⃣ Task Organization Engine
- Manages task creation, updates, and listing using Java Collections  
- Persists task data using JDBC (MySQL / H2)  
- **REST APIs:**
  - `POST /tasks/add`
  - `GET /tasks/list`
  - `PUT /tasks/{id}`

---

### 2️⃣ Scheduling System
- Schedules reminders using `ScheduledExecutorService`  
- Handles concurrent scheduling and notification logic  
- **REST APIs:**
  - `POST /schedule/set`
  - `GET /reminders/{taskId}`

---

### 3️⃣ Overview & CSV Integration Hub
- Generates task summaries and reports  
- Exports reports to CSV format (simulating Google Sheets)  
- Sends reminder emails using JavaMail API  
- **REST APIs:**
  - `GET /reports/overview`
  - `POST /reports/export`

---

### 4️⃣ Completion Tracker
- Marks tasks as completed  
- Provides task status insights  
- **REST APIs:**
  - `PUT /completion/mark`
  - `GET /status/{taskId}`

---

## 🛠️ Technologies Used

- Java (Core Java, Collections, Concurrency)  
- Spring Boot  
- Spring MVC & REST APIs  
- JDBC  
- MySQL / H2 Database  
- JavaMail API  
- CSV File Handling  
- Maven / Gradle  

---

## 📆 Project Milestones

### 🔹 Milestone 1 (Weeks 1–2): Setup & Training
- JDK and database setup  
- Spring Boot configuration  
- Training on timers, collections, JDBC, and REST APIs  
- Task entity and data model design  

---

### 🔹 Milestone 2 (Weeks 3–4): Task Organization Engine
- Implement task management using collections  
- JDBC integration in Spring Boot  
- Develop and test task-related REST APIs  

---

### 🔹 Milestone 3 (Weeks 5–6): Scheduling & Reporting
- Implement reminder scheduling logic  
- CSV export and email notification integration  
- Develop APIs for scheduling and reports  

---

### 🔹 Milestone 4 (Weeks 7–8): Completion Tracking & Deployment
- Completion tracking and status insights  
- End-to-end testing  
- Application deployment and API validation  

---
## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/task-reminder-app.git

---
## 2️⃣ Configure Database

Update the database configuration in application.properties
(You can use MySQL or H2 as️as per your setup).
---
### 3️⃣ Build and Run the Application
mvn spring-boot:run
---

### 4️⃣ Access the APIs
http://localhost:8080
---

### 📌 Future Enhancements

Role-based authentication (JWT / OAuth)

UI frontend using React or Angular

Push notifications

Analytics dashboard
---

### 👤 Author

Syed Yasmin
Java & Spring Boot Developer
