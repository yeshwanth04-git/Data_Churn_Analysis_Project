# Data_Churn_Analysis_Project
An ABC bank wants to perform customer churn analytics based on the data, to find out the potential customers who have exited the bank, based on the following analytics.

Customer Churn Analytics – Banking (Databricks)

Overview
This project implements an end‑to‑end data pipeline using Databricks and Delta Lake to perform customer churn analytics for a bank.
The solution follows the Medallion Architecture (Bronze, Silver, Gold) to transform raw CSV data into business‑ready KPI datasets and dashboards.

Architecture

Bronze – Raw data ingestion and staging (Delta tables)
Silver – Data cleansing, deduplication, and standardization
Gold – Business KPIs and analytical datasets


Data Sources

customer.csv – Customer demographics, tenure, credit score, churn status
account.csv – Account balance and product details


Pipeline Summary

Ingest raw CSV data into Bronze layer
Clean and standardize data in Silver layer
Build churn‑related KPIs in Gold layer
Visualize insights using Databricks dashboards


KPIs Implemented

High‑balance customers who exited
Retained customers with good credit and multiple products
Active high‑value female customers
Long‑tenure customers by geography and gender
Geography with most inactive customers
Active young customers (≤ 35) by geography
Active customers with zero balance
High‑salary customers (> 12L annually)


Technologies Used
Databricks
Apache Spark (PySpark)
Delta Lake
Medallion Architecture
Databricks Dashboards
