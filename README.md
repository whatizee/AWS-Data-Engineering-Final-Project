# AWS Data Engineering Capstone Project

## Project Overview
This repository contains the capstone project for the AWS Data Engineering course offered by AWS Academy. The project demonstrates an end-to-end ETL workflow using various AWS services, enabling data extraction, transformation, loading, querying, and visualization.

## Workflow

1. **Data Extraction**: 
   - Raw data is extracted from an Amazon S3 bucket.

2. **Data Transformation**:
   - Using the Pandas framework in AWS Cloud9 IDE, the data is transformed into Apache Parquet format.

3. **Data Loading**:
   - The transformed data is loaded back into an Amazon S3 bucket and queried using S3 Select.

4. **Metadata and Schema Extraction**:
   - AWS Glue and its crawler are utilized to create tables and extract metadata/schema from the S3 data.

5. **Data Querying and Transformation**:
   - Amazon Athena is used to query and transform the Glue table data into views for analysis.

6. **Data Visualization**:
   - Amazon QuickSight is employed to visualize the final datasets and create interactive dashboards.

## Repository Contents

- **Final Capstone Project.md**: Step-by-step documentation of the project implementation, including outputs and visualizations.
- **ETL Scripts**: Python scripts and other resources used for transforming and loading data.
- **Visualization Outputs**: Snapshots of dashboards and data visualizations created in Amazon QuickSight.

## AWS Services Used

- **Amazon S3**: For data storage and retrieval.
- **AWS Cloud9 IDE**: For transformation using the Pandas framework.
- **AWS Glue**: For creating tables, metadata extraction, and schema generation.
- **Amazon Athena**: For querying and transforming data.
- **Amazon QuickSight**: For creating visualizations and dashboards.

## How to Use
1. Clone this repository to your local machine.
2. Follow the instructions in **Final Capstone Project.md** to replicate the project workflow.
3. Review the ETL scripts and adjust them as needed for your dataset.
4. Explore the visualization outputs for insights or create your own dashboards using Amazon QuickSight.

## Key Highlights
This project provides practical insights into cloud-based data engineering workflows, leveraging AWS tools to process, analyze, and visualize data efficiently. It's a hands-on demonstration of applying data engineering concepts in real-world scenarios.

Feel free to explore, modify, and utilize this repository for your own projects!
