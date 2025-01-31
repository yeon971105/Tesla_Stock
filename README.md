# Tesla Stock Analysis

This project focuses on analyzing and predicting Tesla's stock price movements using various statistical and machine learning techniques. Developed as part of the Data Science program at San Jose State University, this project leverages Python and several data analysis libraries to forecast future stock prices, offering valuable insights into financial market trends.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Data Collection](#data-collection)
- [Analysis Techniques](#analysis-techniques)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## Overview
The primary goal of this project is to employ statistical analysis and machine learning models to predict the price movements of Tesla, Inc. stocks. By doing so, this project aims to provide tools that could potentially help investors make more informed decisions.

## Technologies Used
- **Python**: Main programming language used for data manipulation and analysis.
- **Pandas & NumPy**: For data manipulation and numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-Learn**: For implementing machine learning algorithms.

## Data Collection
The data consists of historical stock prices of Tesla, Inc., which includes daily open, high, low, close prices, and volume. The data was sourced from Yahoo Finance, covering the period from January 2020 to December 2023.

## Analysis Techniques
1. **Statistical Analysis**: Initial exploration of data using statistical methods to identify trends, seasonality, and anomalies.
2. **Time Series Analysis**: Employed to understand the time-dependent patterns and forecast future stock movements.
3. **Machine Learning Models**: Utilization of models like Linear Regression and Random Forest to predict future prices based on historical data.

## Results
The project succeeded in applying various analysis techniques to predict stock price movements with a considerable degree of accuracy:
- **Linear Regression Model**: Achieved an accuracy of 75%.
- **Random Forest Model**: Surpassed the Linear Model with an accuracy of 82%.

## Installation
To run this project locally, follow these steps:
```bash
git clone https://github.com/your-username/tesla-stock-analysis.git
cd tesla-stock-analysis
pip install -r requirements.txt
