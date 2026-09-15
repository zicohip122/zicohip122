# 🍪 Cookies Sales Dashboard – Power BI

### 🔗 [My LinkedIn](https://www.linkedin.com/in/your-profile/)
### 📥 [Download the PBIX File](https://github.com/your-username/your-repo/blob/main/assets/Cookies.pbix?raw=true)
### 📊 [View Interactive Dashboard on NovyPro](https://your-novypro-link.com)

<br>
<div align="center">
  <img src="https://github.com/your-username/your-repo/blob/main/assets/banner.png?raw=true" alt="Cookies Dashboard Banner" width="1000" height="500">
</div>

---

## 📝 Introduction
<details>
  <summary><strong>📌 Overview (click)</strong></summary>

### **Overview**  
> This Power BI project analyzes the sales performance of a Cookies Shop. It uncovers key metrics around **sales trends**, **customer behavior**, **product preferences**, and **sales by location or time**.  
> The dashboard is designed to help business stakeholders make better decisions by identifying best-selling products, customer buying patterns, and underperforming areas.

</details>

<details>
  <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The dataset includes multiple tables capturing essential data about orders, customers, and product inventory.

**▼ 📑Dataset Explanation**  
1. **Sales Table**
   - `Order ID`: Unique identifier for each order  
   - `Customer ID`: Reference to the customer who placed the order  
   - `Product`: Name/type of the cookie sold  
   - `Category`: Product category  
   - `Order Date`: Date of transaction  
   - `Quantity`: Units sold  
   - `Unit Price`: Price per item  
   - `Total Sales`: Revenue from the order  

2. **Customer Table**
   - `Customer ID`: Unique identifier for each customer  
   - `Name`: Full name  
   - `Segment`: Customer group/type  
   - `Location`: City or region  

3. **Product Table**
   - `Product ID`: Unique product identifier  
   - `Product Name`: Name of the cookie  
   - `Category`: Classification (e.g., Premium, Classic, Vegan)  
   - `Cost`: Cost per unit  

</details>

---

## 🎯 Case Study  
The Cookies Shop has grown rapidly, but management noticed fluctuations in revenue and product demand. They needed a visual dashboard to:
- Track monthly sales trends and profitability  
- Identify top-performing and least-selling cookies  
- Understand customer behavior and segmentation  
- Optimize inventory and marketing efforts based on data  

---

## 📊 Main KPIs
- **💰 Total Sales**: Sum of all order values  
- **📦 Total Orders**: Count of unique orders  
- **👥 Total Customers**: Distinct customers who purchased  
- **🏆 Best-Selling Products**: Ranked by revenue or quantity  
- **📉 Low Performing Products**: Cookies with least contribution  
- **🕒 Sales by Time**: Monthly/weekly trend of orders  
- **📍 Sales by Location**: Performance by region or city  
- **📊 Customer Segments**: Analysis by customer group  

---

## ⚙️ Process
1. Imported data into Power BI from Excel  
2. Cleaned and transformed tables using Power Query  
3. Built relationships and a star schema data model  
4. Created DAX measures for KPIs and dynamic insights  
5. Designed interactive visuals and slicers for user exploration  

---

## 📐 Data Model  
![Data Model](https://github.com/your-username/your-repo/blob/main/assets/data-model.png?raw=true)

---

## 📈 Dashboard Preview  
<img src="https://github.com/your-username/your-repo/blob/main/assets/dashboard-1.png?raw=true" width="1000">
<img src="https://github.com/your-username/your-repo/blob/main/assets/dashboard-2.png?raw=true" width="1000">

---

## 🎥 Project Demo  
<img src="https://github.com/your-username/your-repo/blob/main/assets/demo.gif?raw=true" width="1000">

---

## 🔍 Key Insights
1. **Top Product**: Chocolate Chip Cookies contributed 32% of total revenue  
2. **Sales Peak**: Highest orders placed during weekends, especially on Sundays  
3. **Customer Loyalty**: Premium segment makes up 48% of repeat orders  
4. **Underperformers**: Seasonal flavors had low sales outside of holidays  
5. **Regional Focus**: Sales in Region X dropped 14% last quarter  
6. **Inventory Alert**: Several high-demand cookies showed frequent stockouts  

---

## 💡 Conclusion
This Power BI dashboard empowers the Cookies Shop to make **data-driven decisions**. From boosting sales of trending products to improving customer engagement, the insights drive better business performance.

---

## 🧰 Tools Used
- **Power BI Desktop**  
- **Power Query**  
- **DAX**  
- **Excel (for data prep)**  

---
## 📁 Project Structure

```bash
Cookies-Shop-PowerBI-Dashboard/
│
├── assets/                  # Screenshots, images, GIFs used in README
│   ├── customer_report.png
│   ├── video.gif
│   ├── dashboard-1.png
│   ├── dashboard-2.png
│   └── dashboard-3.png
│
├── data/                    # (Optional) Sample dataset files
│   └── sales_data_sample.xlsx
│
├── pbix/                    # Power BI project files
│   └── Cookies.pbix
│
├── docs/                    # Additional documentation (optional)
│   └── project_notes.pdf
│
└── README.md
```
