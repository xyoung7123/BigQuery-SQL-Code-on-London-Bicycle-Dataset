# BigQuery-SQL-Code-on-London-Bicycle-Dataset
Google Data Analytics Course 3, Week 3 on BigQuery Google Cloud Platform(Solutions to questions)
Solution Code to the 4 questions asked on the London Bicycle Hires, Greater London Authority
(Number of hires of the Santander Cycle Hire Scheme) on Google Cloud Platform

SQL codes:

select count(distinct bike_id) from `bigquery-public-data.london_bicycles.cycle_hire`
where end_station_name = "Moor Street, Soho";


select end_station_name, start_station_name from `bigquery-public-data.london_bicycles.cycle_hire`
where start_station_id = 111;


select start_station_id, start_station_name from `bigquery-public-data.london_bicycles.cycle_hire`
where start_station_name = "Canton Street, Poplar";


select count(distinct bike_id) from `bigquery-public-data.london_bicycles.cycle_hire`
where duration > 2400;
