# www.srmosi-vdp.in
# SRM OSI Backend

## Setup Instructions

1. Run `npm install` in the backend folder to install dependencies.
2. Ensure your MySQL server is running and create the database and table with:

   ```sql
   CREATE DATABASE srm_osi;
   USE srm_osi;
   CREATE TABLE members (
     id INT AUTO_INCREMENT PRIMARY KEY,
     name VARCHAR(255) NOT NULL,
     email VARCHAR(255) NOT NULL,
     department VARCHAR(255) NOT NULL
   );
