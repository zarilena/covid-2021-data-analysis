# COVID-19 Data Analysis (2021) – Practice Exercise

A beginner-friendly data analysis and visualization exercise in Python using public COVID-19 data from **Our World in Data (OWID)** for the year **2021** across eight selected countries: Greece, Italy, Germany, France, Spain, the United States, Japan, and Brazil.

## What This Notebook Covers
- **Filtering & Preparation:** Selecting 2021 records, target countries, and key columns (`continent`, `country`, `date`, `population`, `new_cases`, `new_deaths`, `total_cases`, `total_deaths`, `people_vaccinated`, `total_vaccinations_per_hundred`, `gdp_per_capita`), followed by sorting by country and date.
- **Data Cleaning:** Checking missing values and duplicates, filling missing daily case/death counts with `0`, inspecting negative values, and interpolating vaccination series per country.
- **Analysis & Normalization:** Computing average and maximum daily new cases and deaths per country, comparing raw totals against population-normalized metrics (`cases_per_100k` and `deaths_per_100k`), and checking vaccination indicators by country and continent.
- **Visualizations:**
  - Line chart of cumulative cases over time across the eight countries
  - Bar chart of total deaths per country
  - Scatter plot comparing total vaccinations per hundred against deaths per 100k
  - Pie chart showing total deaths by continent across the sampled countries

## Tools & Libraries
- Python
- `pandas`
- `numpy`
- `matplotlib`

## Summary of Findings
Based on the 2021 COVID-19 data for the eight selected countries, cumulative cases increased steadily over the course of the year. In raw numbers, the United States and Brazil recorded the highest total cases and deaths, influenced heavily by population size. Normalizing by population (`per 100k`) changes how countries compare relative to their size, and higher vaccination coverage generally aligns with lower deaths per 100k within this sample.

## Note
This project was created as a practical data analysis exercise during training at TechPro Academy and uses live public data from Our World in Data, which may reflect subsequent dataset updates.
