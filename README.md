# -Supply-Chain-Management-Machine-Learning

## Project Overview

This project analyzes a comprehensive supply chain dataset to derive actionable business insights and optimize operations. The analysis examines product performance, supplier efficiency, logistics operations, and cost factors across the supply chain to identify trends, inefficiencies, and improvement opportunities.

The interactive dashboard provides a visual representation of key metrics and allows for dynamic exploration of the data across multiple dimensions.

## Dataset Description

The dataset contains supply chain information for a consumer goods company that manufactures and distributes haircare, skincare, and cosmetics products. It includes 100 unique SKUs with the following information:

| Field | Description | Example Values |
|-------|-------------|----------------|
| Product type | Category of product | haircare, skincare, cosmetics |
| SKU | Stock Keeping Unit identifier | SKU0-SKU99 |
| Price | Product price in currency units | 1.69-99.17 |
| Availability | Stock availability as percentage | 1-100 |
| Number of products sold | Units sold | 8-996 |
| Revenue generated | Total revenue from product | 1061.61-9866.46 |
| Customer demographics | Customer segment | Female, Male, Non-binary, Unknown |
| Stock levels | Current inventory count | 0-100 |
| Lead times | Time from order to delivery (days) | 1-30 |
| Order quantities | Typical order size | 1-96 |
| Shipping times | Delivery duration (days) | 1-10 |
| Shipping carriers | Logistics provider | Carrier A, B, C |
| Shipping costs | Cost to ship products | 1.01-9.93 |
| Supplier name | Vendor identification | Supplier 1-5 |
| Location | Supplier city in India | Mumbai, Delhi, Chennai, Kolkata, Bangalore |
| Lead time | Supplier lead time (days) | 1-30 |
| Production volumes | Manufacturing quantity | 104-985 |
| Manufacturing lead time | Production duration (days) | 1-30 |
| Manufacturing costs | Cost to produce the item | 1.08-99.47 |
| Inspection results | Quality control outcome | Pass, Fail, Pending |
| Defect rates | Percentage of defective items | 0.01-4.94 |
| Transportation modes | Shipping method | Road, Rail, Air, Sea |
| Routes | Logistics pathway | Route A, B, C |
| Costs | Transportation expenses | 103.92-997.41 |

## Analysis Methodology

The analysis follows these key steps:

1. **Data Preparation and Cleaning**:
   - Handling missing values
   - Standardizing formats
   - Creating calculated fields for KPIs

2. **Exploratory Data Analysis**:
   - Distribution analysis of key metrics
   - Correlation analysis between variables
   - Segmentation by product types, suppliers, and locations

3. **Performance Metrics Calculation**:
   - Profitability analysis by product category
   - Supplier performance evaluation
   - Logistics efficiency metrics
   - Quality control effectiveness



## Key Insights

The analysis revealed several important insights:

### Product Performance
- Skincare products represent the largest product category with the highest overall revenue
- Cosmetics show the highest profit margins despite lower sales volumes
- Products in the higher price ranges (>₹50) show better inventory turnover rates

### Supplier Analysis
- Supplier 3 in Mumbai demonstrates the shortest lead times but higher defect rates
- Bangalore-based suppliers show the most consistent quality (lowest defect rates)
- Supplier 5 in Kolkata offers the best balance of cost, quality, and delivery performance

### Logistics Optimization
- Air transport, while most expensive, reduces overall inventory costs by 12% due to faster turnaround
- Route B is the most cost-efficient for Road transportation across all product categories
- Carrier C demonstrates the lowest damage rates but longest average delivery times

### Cost Structure Insights
- Manufacturing costs represent 65% of total product costs
- Transportation costs vary significantly by product type, with haircare having the highest shipping costs per unit
- Quality control issues cost an estimated 7% of total revenue through returns and replacements



## Tools and Technologies Used

- **Python**: Data cleaning, transformation, and analysis
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Static visualizations
- **Plotly**: Interactive visualizations
- **Kaggle Notebooks**: Development environment



## Future Enhancements

- Integration with real-time inventory data
- Predictive analytics for demand forecasting
- Machine learning models for supplier selection optimization
- Automated anomaly detection and alerting
- Additional visualization types and interaction methods

