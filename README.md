# FUTURE_DS_02
Customer churn and retention analysis using Power BI, with insights on customer behavior, lifetime trends and strategies to reduce churn.

# 📊 Customer Retention & Churn Analysis Dashboard

# 📌 Project Overview

Customer churn is a critical challenge for subscription-based businesses, directly impacting revenue and growth.
This project analyzes customer data to identify churn patterns, understand retention drivers, and evaluate customer lifetime trends.

An interactive Power BI dashboard was developed to transform raw data into actionable insights for business decision-making.

---

# 🎯 Objectives

* Analyze customer churn behavior and identify high-risk segments
* Understand key factors influencing customer retention
* Evaluate customer lifetime using tenure-based analysis
* Provide data-driven recommendations to reduce churn

---

## 🛠️ Tools & Technologies

* **Power BI** – Data visualization and dashboard creation
* **DAX** – KPI and metric calculations
* **Data Cleaning** – Handling missing values and data transformation

---

## 📂 Dataset

* **Telco Customer Churn Dataset (Kaggle)**
* Includes customer demographics, services, subscription details, and churn status

---

## 📊 Dashboard Structure

### 🔹 Page 1: Churn Overview Dashboard

* KPI Cards (Total Customers, Churn Rate, Avg Tenure)
* Customer Churn Distribution
* Churn by Contract Type, Payment Method
* Customer Distribution by Internet Service
* Churn Trend by Tenure
* Interactive slicers for dynamic filtering

---

### 🔹 Page 2: Churn Insights & Recommendations

* Customer Tenure Distribution
* Churn by Monthly Charges
* Impact of Tech Support and Online Security
* Service Usage vs Churn Analysis
* Customer Behavior (Scatter Analysis)
* Business Insights & Strategic Recommendations

---

## 📈 Key Metrics (DAX Measures)

```DAX
Total Customers = COUNT(CustomerID)

Churn Customers = CALCULATE(COUNT(CustomerID), Churn = "Yes")

Churn Rate = DIVIDE([Churn Customers], [Total Customers])

Avg Tenure = AVERAGE(Tenure)
```

---

## 🔍 Key Insights

* Customers with **month-to-month contracts** exhibit the highest churn rates
* **Higher monthly charges** significantly increase churn probability
* **New customers (low tenure)** are more likely to leave early
* Lack of **tech support and online security** contributes to higher churn
* Customers subscribed to **multiple services** demonstrate stronger retention

---

## 💡 Business Recommendations

* Introduce incentives for **long-term contracts** to improve retention
* Enhance **customer onboarding experience** to reduce early churn
* Offer **bundled services** to increase customer engagement
* Strengthen **customer support systems**
* Optimize pricing strategies for high-cost plans

---

## 📸 Dashboard Preview

### 🔹 Overview Page

![Overview Dashboard](dashboard_overview.png)

### 🔹 Insights Page

![Insights Dashboard](dashboard_insights.png)

---

## 🚀 Business Impact

This analysis highlights how data-driven insights can:

* Reduce customer churn
* Improve retention strategies
* Support better decision-making for business stakeholders

---

## 📌 Conclusion

The project demonstrates the importance of combining data analytics with business understanding to solve real-world problems.
By identifying churn drivers and retention opportunities, organizations can enhance customer satisfaction and long-term profitability.

---

## 🔗 Project Links

* 📂 GitHub Repository: (Add your link)
* 📊 Dashboard File: (Optional link if hosted)

---

## 🙋‍♀️ Author

**Zainab Mapkar**
Aspiring Data Analyst | Power BI Enthusiast

---
