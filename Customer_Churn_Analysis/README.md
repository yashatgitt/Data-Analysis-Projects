
# Customer Churn Analysis (Data Analyst Project)

## 📌 Project Overview

Customer churn is a major business challenge where customers stop using a company’s services. Retaining existing customers is often more cost-effective than acquiring new ones. This project focuses on analyzing customer churn data to identify **key factors that influence customer attrition** and to provide **actionable business insights**.

This project is designed as a **Data Analyst portfolio project**, emphasizing data cleaning, exploratory data analysis (EDA), visualization, and business interpretation rather than complex machine learning.

---

## 🎯 Objectives

* Understand customer behavior using historical data
* Identify key factors contributing to customer churn
* Perform exploratory data analysis (EDA) using Python
* Visualize trends and patterns related to churn
* Provide business recommendations to reduce churn

---

## 🛠 Tools & Technologies Used

* **Programming Language:** Python
* **Libraries:**

  * pandas – data manipulation and analysis
  * NumPy – numerical operations
  * Matplotlib – data visualization
  * Seaborn – statistical visualization
* **Environment:** Google Colab / Jupyter Notebook

---

## 📂 Dataset Information

* **Dataset Name:** Telco Customer Churn Dataset
* **Source:** Kaggle
* **Records:** 7,043 customers
* **Features:** 21 columns

### Key Columns:

* `gender`
* `SeniorCitizen`
* `tenure`
* `MonthlyCharges`
* `TotalCharges`
* `Contract`
* `PaymentMethod`
* `Churn` (Target Variable: Yes / No)

---

## 🔍 Project Workflow

### 1️⃣ Data Loading

* Loaded CSV dataset using pandas
* Verified dataset size and structure

### 2️⃣ Data Understanding

* Examined data types and column meanings
* Identified numerical and categorical features
* Checked churn distribution

### 3️⃣ Data Cleaning

* Converted `TotalCharges` from object to numeric
* Handled hidden missing values
* Ensured dataset was ready for analysis

### 4️⃣ Exploratory Data Analysis (EDA)

Performed EDA to uncover patterns and trends related to churn:

#### 🔹 Churn Distribution

* Approximately **26.5% of customers churned**

#### 🔹 Monthly Charges vs Churn

* Customers with **higher monthly charges** are more likely to churn

#### 🔹 Tenure vs Churn

* Customers with **lower tenure** (new customers) show higher churn

#### 🔹 Contract Type vs Churn

| Contract Type  | Churn Percentage |
| -------------- | ---------------- |
| Month-to-month | ~42.7%           |
| One year       | ~11.3%           |
| Two year       | ~2.8%            |

* Month-to-month contracts have the **highest churn rate**
* Long-term contracts significantly improve retention

---

## 📊 Key Insights

* Around **1 in 4 customers churn**, indicating a serious retention issue
* High monthly charges strongly correlate with churn
* New customers are more likely to leave early
* Long-term contracts drastically reduce churn probability

---

## 💡 Business Recommendations

* Encourage customers to move from month-to-month to long-term contracts
* Offer discounts or loyalty benefits to high-paying customers
* Focus retention strategies on new customers during early tenure
* Use churn insights to design targeted marketing campaigns

---

## 📈 Outcome

This project demonstrates the ability to:

* Work with real-world, messy datasets
* Apply data cleaning and EDA techniques
* Translate data findings into business insights
* Communicate results clearly using visualizations and written conclusions

---

## 📁 How to Run This Project

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the dataset CSV file
3. Run cells sequentially from top to bottom
4. Review visualizations and insights in the notebook

---

## 📌 Author

**Yash Sandip Gangurde**
Aspiring Data Analyst
📧 [yash.gangurde001@gmail.com](mailto:yash.gangurde001@gmail.com)
🔗 GitHub: [https://github.com/yashatgitt](https://github.com/yashatgitt)
🔗 LinkedIn: [https://www.linkedin.com/in/yash-gangurde-95557328b/](https://www.linkedin.com/in/yash-gangurde-95557328b/)

---

## ✅ Status

✔ Completed – Portfolio Ready Data Analyst Project
