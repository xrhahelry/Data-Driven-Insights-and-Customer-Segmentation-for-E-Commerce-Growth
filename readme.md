# Data-Driven Insights and Customer Segmentation for E-Commerce Growth 
> View the **Final Report.pdf** to see the results of the project

In today's competitive e-commerce landscape, data-driven decision-making
is essential for business growth and customer satisfaction. This project
applies advanced data mining techniques to analyze transactional data
from a London-based online retailer, aiming to extract actionable
insights into customer behavior, product associations, and sales trends.
Exploratory Data Analysis (EDA) and data cleaning were performed to
handle inconsistencies and outliers, followed by feature engineering
including RFM (Recency, Frequency, Monetary) metrics and dimensionality
reduction using Principal Component Analysis (PCA). K-means clustering
identified distinct customer segments, with cluster evaluation guided by
silhouette scores and sum of squared errors. Market Basket Analysis,
through the Apriori algorithm, revealed strong product associations both
within the UK and in international markets by excluding UK data. The
findings highlight key customer segments and product combinations,
offering valuable directions for personalized marketing, inventory
management, and market expansion strategies. This study demonstrates the
power of data mining to optimize e-commerce operations and enhance
targeted business strategies.

## Objectives

Providing actionable insights to support the future growth of the
business by:

-   Identifying trends in purchase behavior and customer preferences,
    helping to understand how buying patterns evolve over time.

-   Analyzing the most profitable products and high-value customer
    segments, enabling more targeted and effective personalized
    marketing strategies.

-   Analyzing the most profitable products and high-value customer
    segments, enabling more targeted and effective personalized
    marketing strategies.

## Research Questions

1.  What products generate the highest revenue?

2.  Which transactions were most profitable?

3.  What is the distribution of customers according to country?

4.  Which countries generate the highest revenue?

5.  What do the sales look like through the months?

6.  How many items are bought together on average?

7.  Which country is the most ideal for expansion?

8.  Who are the most valuable customers?

9.  Which customers are at risk of churning?

10. What are the strongest product associations?

11. What are the strongest product associations outside the UK?

12. How is price affecting the sales of top 10 products?

# Dataset Introduction
The dataset used is from [kaggle](https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business/data)

Dataset consists of sales transaction data of UK-based e-commerce for
one year (2018-2019). This London-based shop has been selling gifts and
homewares for adults and children through the website since 2007.

The Dataset consists of 500K rows and 8 columns. The following is the
description of each column.

1.  TransactionNo (categorical): a five or six-digit unique character
    used to identify a specific transaction.

2.  Date (numeric): the date when each transaction was generated.

3.  Product (categorical): product/item name.

4.  ProductNo (categorical): a five or six-digit unique character used
    to identify a specific product.

5.  Price (numeric): the price of each product per unit in pound
    sterling.

6.  Quantity (numeric)

7.  CustomerNo (categorical): a five-digit unique number that defines
    each customer.

8.  Country (categorical): name of the country where the customer
    resides.

