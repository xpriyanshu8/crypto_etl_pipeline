# Crypto ETL Data Pipeline 

An end-to-end data pipeline that fetches real-time cryptocurrency data using the CoinGecko API, transforms and cleans it using Pandas, stores raw and processed data in AWS S3, and loads final results into a PostgreSQL database. The entire pipeline is scheduled and orchestrated using Apache Airflow.

## Stack
- Python
- AWS S3
- PostgreSQL
- Apache Airflow
- Pandas

## Use Cases
- Track daily price & volume trends
- Build dashboards for crypto analysis
- Practice building production-ready pipelines

## DAG Schedule
Runs every day at 6 AM IST
