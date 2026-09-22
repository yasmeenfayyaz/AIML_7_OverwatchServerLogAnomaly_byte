# Task 7: The "Overwatch" Server Log Anomaly (Unsupervised Threat Detection)

## Overview
This repository contains the solution for **AVIP Task 7**, focusing on unsupervised anomaly detection in large-scale server logs using Machine Learning (`Isolation Forest`).

## Deliverables
- **`training_notebook.ipynb`**: Google Colab notebook containing complete exploratory data analysis, log parsing, feature extraction, and model training.
- **`inference.py`**: Python script for parsing raw server logs and predicting threats on new log files.
- **`threat_intelligence_report.txt`**: Detailed cybersecurity threat analysis and mitigation report.

## Tech Stack
- **Python**
- **Pandas & NumPy** (Data Manipulation)
- **Scikit-Learn** (Isolation Forest & Standardization)
- **Regex** (Log Parsing)

## How to Run
1. Place your target server log file as `logfiles.log` in the directory.
2. Run the inference script:
   ```bash
   python inference.py
