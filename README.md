# Movie Data Engineering Project
## Overview
I'm excited to share the progress in my data engineering studies! 🚀 .
This project focuses on collecting, preparing, and serving data related to movies. The primary goal is to gain insights into the likability and length of movies, providing valuable information for understanding audience preferences and movie characteristics.


In this repository, I explore one of the many possible options for implementing an ETL pipeline.

- I'm using two types of data sources, a local one represented by a MySQL database, and a remote one represented by a Public API. 🏛️🌐
- In the two working notebooks (API_ETL.ipynb, etl.ipynb), I explore two ways of transforming data. The first method uses a Pandas transformation in a local environment, and the second involves executing a data extraction using an API with the necessary transformations to add business context to the data making it ready for analysis. 📊🔄
- Finally, using Python libraries for Google Cloud Platform, I store these analysis-ready data in BigQuery, completing the ETL process. 🐍🔍📊

As a conclusion from the course (ETL using Python: from MySQL to BigQuery), I understand that many performance improvements can be implemented, and I can explore new tools for storing my data. I also recognize that in modern data architectures, the ELT approach is more suitable. 🛠️💡

I continue my studies to deepen my knowledge in Cloud AWS. ☁️📚

## Key Features
- Data Collection: Utilized mysql as a  data source to gather comprehensive information about movies.
- Data Preparation:  Transformed, and enriched the data to ensure its accuracy and usefulness using python
- BigQuery Integration: Implemented a seamless integration with Google BigQuery for efficient storage and retrieval of movie data.


## Technologies Used
- Data Collection: Python
- Data Processing: Pandas
- Datasource : MYSQL , API
- Data Lake : Google BigQuery


## How to Use 
1. Clone the Repository:
```
git clone https://github.com/yakobodata/Extract_Load_Transform
```

2. Install dependencies
```
pip install -r requirements.txt
```

## Contributors
WAMANI JACOB(https://github.com/yakobodata)
RODRIGO TAKESHI(https://github.com/rtakeshi)
