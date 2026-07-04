# Google Maps Reviews Analysis Using Big Data & NLP

> A Big Data pipeline for analyzing over one million Google Maps reviews
> from tourist and entertainment destinations across Saudi Arabia using
> Apache Spark, CAMeLBERT, and interactive Power BI dashboards.

------------------------------------------------------------------------

## Overview

This project presents an end-to-end Big Data solution for processing and
analyzing large-scale Arabic textual reviews collected from Google Maps.
The system leverages distributed computing technologies to efficiently
handle more than one million visitor reviews and applies Natural
Language Processing (NLP) techniques to extract valuable insights about
visitor satisfaction.

The project combines Big Data infrastructure, sentiment analysis,
aspect-based opinion mining, and business intelligence dashboards to
support data-driven decision-making for the tourism sector in Saudi
Arabia.

------------------------------------------------------------------------

## Objectives

-   Collect large-scale Google Maps reviews from tourist destinations.
-   Build a complete Big Data processing pipeline.
-   Process and clean Arabic textual data.
-   Perform sentiment analysis using CAMeLBERT.
-   Extract visitor opinions using Aspect-Based Sentiment Analysis.
-   Optimize storage using Apache Parquet.
-   Visualize insights through interactive Power BI dashboards.

------------------------------------------------------------------------

## Project Architecture

``` text
Google Maps
      │
      ▼
Apify Data Collection
      │
      ▼
CSV Dataset
      │
      ▼
HDFS Distributed Storage
      │
      ▼
Apache Spark (PySpark)
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Parquet Optimization
      │
      ▼
CAMeLBERT Sentiment Analysis
      │
      ▼
Aspect-Based Analysis
      │
      ▼
Power BI Dashboards
```

------------------------------------------------------------------------

## Dataset

The dataset consists of **1,000,000+ Arabic reviews** collected from
Google Maps covering tourist and entertainment destinations across all
regions of Saudi Arabia.

### Dataset Features

-   Tourist destination
-   City
-   Region
-   Latitude & Longitude
-   Review text
-   Rating
-   Date
-   Category

------------------------------------------------------------------------

## Technologies Used

  Category           Technologies
  ------------------ -----------------------------
  Programming        Python
  Big Data           Apache Spark, PySpark, HDFS
  Storage            CSV, Apache Parquet
  Data Collection    Apify, Google Maps
  NLP                CAMeLBERT
  Machine Learning   Transformers
  Visualization      Power BI
  Development        Google Colab, Kaggle

------------------------------------------------------------------------

## Data Processing Pipeline

1.  Collect reviews using Apify.
2.  Store raw datasets in HDFS.
3.  Process distributed data using Apache Spark.
4.  Clean and normalize Arabic text.
5.  Convert datasets into Parquet format.
6.  Perform sentiment classification with CAMeLBERT.
7.  Extract service aspects using a rule-based dictionary.
8.  Generate interactive dashboards in Power BI.

------------------------------------------------------------------------

## Key Features

-   Large-scale distributed data processing
-   Arabic NLP pipeline
-   Sentiment Analysis
-   Aspect-Based Sentiment Analysis (ABSA)
-   Big Data architecture
-   Distributed storage with HDFS
-   Optimized Parquet storage
-   Interactive Business Intelligence dashboards

------------------------------------------------------------------------

## Results

  Metric                   Score
  -------------------- ---------
  Overall Accuracy       **93%**
  Positive Precision     **94%**
  Positive Recall        **99%**
  Positive F1-Score      **96%**
  Negative Precision     **81%**
  Negative Recall        **45%**
  Negative F1-Score      **58%**

The CAMeLBERT model achieved strong performance in classifying Arabic
tourism reviews, demonstrating the effectiveness of combining Big Data
technologies with transformer-based NLP models.

------------------------------------------------------------------------

## Dashboard Insights

-   Visitor satisfaction analysis
-   Positive vs. negative sentiment distribution
-   Regional comparison across Saudi Arabia
-   City-level analytics
-   Category performance
-   Aspect-based satisfaction indicators
-   Interactive geographical visualization

------------------------------------------------------------------------

## Repository Structure

``` text
Google-Maps-BigData-Analysis
│
├── Data/
├── Notebooks/
├── Models/
├── Dashboards/
├── Results/
├── Images/
├── Report/
└── README.md
```

------------------------------------------------------------------------

## Future Improvements

-   Multi-class sentiment classification
-   Real-time data streaming
-   Topic Modeling
-   Recommendation system
-   Cloud deployment

------------------------------------------------------------------------

## Author

**Yazan Ibrahim Alghamdi**

Data Science Graduate --- Umm Al-Qura University

------------------------------------------------------------------------

> Developed as part of the Big Data Mining course to demonstrate
> practical applications of distributed computing, Arabic NLP, and
> Business Intelligence for tourism analytics.
