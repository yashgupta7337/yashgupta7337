### Yash Gupta

Data Engineer · Bangalore, India  
[buildwithmiyazaki.dev](https://buildwithmiyazaki.dev) · [yashgupta1470@gmail.com](mailto:yashgupta1470@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yashgupta7337)

I independently own and scale data platforms in fast-paced, lean environments — leading critical migrations and architectural shifts that cut query latency by 90%+ and infrastructure cost by 35–40%. I specialize in cost-efficient, reliable pipelines and real-time systems.

---

**What I shipped at Connect and Heal (Jun 2024 → Present)**

| Result | What I did |
|---|---|
| 90%+ query latency cut | Migrated cloud-native lakehouse → ClickHouse; queries went from 60 s to ~5 s |
| 40% Aurora cost reduction | Consolidated AWS Aurora Postgres across prod and lower environments |
| 300 GB migrated, zero downtime | DocumentDB → Aurora Postgres: unstructured → structured, no row dropped |
| 35% lakehouse cost reduction | Re-architected medallion lakehouse on S3 + Hudi + EMR + Glue + MWAA |

---

**Stack**

```
Source ──► Ingest ──────────────► Process ──────────► Store ──────────────► Serve
           S3 · DMS · Lambda        Spark · EMR · dbt    ClickHouse · Hudi     Metabase
           Glue · Airflow (MWAA)    Python · SQL          Iceberg · PostgreSQL  Dashboards
                                    Dagster                Aurora · DynamoDB     Athena
```

[![Python](https://skillicons.dev/icons?i=python)](https://skillicons.dev)
[![Docker](https://skillicons.dev/icons?i=docker)](https://skillicons.dev)
[![Kubernetes](https://skillicons.dev/icons?i=kubernetes)](https://skillicons.dev)
[![AWS](https://skillicons.dev/icons?i=aws)](https://skillicons.dev)
[![PostgreSQL](https://skillicons.dev/icons?i=postgresql)](https://skillicons.dev)
[![Git](https://skillicons.dev/icons?i=git)](https://skillicons.dev)

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Apache Hudi](https://img.shields.io/badge/Apache%20Hudi-00A1E4?style=flat-square&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white)

---

**Featured projects**

[**Stock Market Data Pipeline**](https://github.com/yashgupta7337/stock_market_airflow) — End-to-end Airflow + Spark pipeline: ingest daily stock data, transform with dockerized Spark, store in MinIO (S3-compatible) and PostgreSQL, visualize in Metabase.  
`Airflow` `Spark` `Docker` `MinIO` `PostgreSQL` `Metabase`

[**AI-Generated Fashion Design**](https://github.com/yashgupta7337/Fashion-NST-GAN) — Neural Style Transfer + GANs to blend artistic styles into unique patterns. 2nd place at NUS for innovation.  
`Python` `NST` `GANs` `Deep Learning`

---

[![Portfolio](https://img.shields.io/badge/Portfolio-buildwithmiyazaki.dev-22d3ee?style=flat-square)](https://buildwithmiyazaki.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yashgupta7337-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashgupta7337)
