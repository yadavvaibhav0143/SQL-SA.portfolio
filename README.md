# SQL Portfolio Analysis – Banking Customer Performance

## Project Overview

This project analyzes a banking customer portfolio dataset using SQL Server to evaluate customer engagement, churn behavior, revenue efficiency, and portfolio growth trends. The objective is to build a structured KPI layer that supports data-driven decision-making at a portfolio level.

### Business Objectives

-Measure overall portfolio performance year-over-year
-Track active customer percentage
-Monitor churn trends
-Evaluate cross-sell effectiveness
-Analyze revenue efficiency using LTV:CAC
-Assess ETB vs NTB portfolio contribution
-Calculate YoY portfolio growth

### Dataset Description

The dataset contains customer-level banking information including:
-Customer Type (ETB / NTB)
-Financial metrics (Average Balance, Revenue, Acquisition Cost)
-Engagement indicators (Active Flag, Cross-Sell Count)
-Churn Flag
-Customer Lifetime Years
-Year-wise portfolio data

### Key KPIs Implemented

#### Active Accounts %
Percentage of customers actively engaged each year.

#### Average Balance per Account
Measures overall portfolio quality and customer value.

#### Churn Rate %
Tracks customer attrition trend year-over-year.

#### Cross-Sell Ratio
Average number of additional products held per customer.

#### ETB vs NTB Contribution
Analyzes balance contribution split between:
-ETB (Existing to Bank)
-NTB (New to Bank)

#### Year-over-Year Portfolio Growth
Calculated using window function (LAG) to measure portfolio expansion rate.

#### LTV : CAC Ratio
Evaluates profitability efficiency of customer acquisition.
