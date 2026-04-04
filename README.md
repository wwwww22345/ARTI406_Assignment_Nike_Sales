# ARTI406_Assignment_Nike_Sales

## Overview
Exploratory Data Analysis (EDA) on Nike's uncleaned sales dataset. In this project indicates data cleaning, visualization, and insight generation techniques for a retail sales dataset.

## Dataset
- **Source:** Kaggle - Nike Sales (Uncleaned Dataset)
    - https://www.kaggle.com/datasets/nayakganesh007/nike-sales-uncleaned-dataset 
- **Original size:** 2,500 rows, 13 columns
- **Clean size:** 110 rows, 16 columns

## Feature Descriptions

- **Order_ID**: Unique identifier
- **Gender_Category**: Customer groups (Men, Women, Kids)
- **Product_Line**: Product category (Running, Basketball, Lifestyle, Training, Soccer)
- **Product_Name**:product name
- **Size**: Product size (S, M, L, XL, Not Specified, etc.)
- **Units_Sold**: Purchased quantity per transaction
- **MRP**: Maximum Retail Price
- **Discount_Applied**: Discount percentage (as decimal)
- **Revenue**: Final amount paid after discount
- **Order_Date**: Transaction date
- **Sales_Channel**: Online or Retail
- **Region** - Indian city of sale
- **Profit** - Profit from transaction

## Data Issues in Original Dataset
- Missing values (Size, Units_Sold, MRP, Discount_Applied, Order_Date)
- Negative and zero values in (Units_Sold,Revenue)
- Discounts exceeding 100%
- Mixed date formats
- Typos in Region names

## Purpose of Dataset
This dataset is used for practicing data cleaning techniques and performing Exploratory Data Analysis (EDA) to identify sales patterns including best performing products, revenue by region and channel, seasonal trends, and customer segment analysis.

