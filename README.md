# 🔐 Security Log Analysis with Python

## 📌 Project Overview
This project focuses on analyzing web server log files to detect suspicious and abnormal activities.
It aims to demonstrate how Python can be used for basic cybersecurity tasks such as log analysis,
pattern detection, and identification of potential attacks.

---

## 🎯 Objectives
- Aalyse web server log files 
- Identify suspicious IP adresses 
- Detect unususal HTTP methods  (GET,PUT, DELETE, POST on admin paths)
- Analyze HTTP status codes (404, 500, etc.)
- Highlight abnormal behaviors in access patterns

---

## 🧰 Tools & Technologies
- Python
- Pandas (data manipulation)
- Matplotlib (visualization)
- Regular Expressions (log parsing)
- Google Colab
- GitHub

---

## 📂 Dataset
The dataset consists of web server access logs containing:
- IP address
- Timestamp
- HTTP method
- Requested URL
- HTTP status code
- User-Agent

---

## 🔍 Key Analysis Performed
- Frequency analysis of IP addresses
- Detection of suspicious HTTP methods
- Identification of failed requests (404, 500)
- Detection of access to sensitive paths (e.g. `/admin`, `/login`)
- Visualization of traffic patterns

---

## 📊 Results & Insights
- Most requests are benign (GET requests)
- Some IPs perform unusual actions such as PUT or DELETE requests
- Requests targeting admin endpoints were detected
- Certain HTTP error codes indicate possible probing attempts

---

## 🚀 Conclusion
This project demonstrates how Python can be used to analyze security logs
and identify potential security threats. It serves as an introductory
cybersecurity and data analysis project.

---

## 👩‍💻 Author
**Yasmin Mrabet**
