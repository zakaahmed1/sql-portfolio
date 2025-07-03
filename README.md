# SQL Portfolio

Welcome to my SQL portfolio! This project showcases my ability to query and analyse relational databases using MySQL. It includes hands-on SQL exercises inspired by platforms like SQLZoo and demonstrates a range of core database skills.

## Databases Used

- `world` – Data about countries, cities, and languages
- `euro2012` – European Championship football stats

## Skills Demonstrated

The SQL files include progressive examples of:

- **SELECT basics**
  - Retrieving columns, filtering rows
- **Filtering and WHERE conditions**
  - Including numeric and string filters
- **SELECT from specific databases**
  - Working with `world`, `euro2012`, etc.
- **Nested SELECT statements**
- **Aggregations**
  - `COUNT`, `SUM`, `AVG`, `GROUP BY`, `HAVING`
- **Joins**
  - Inner joins, self joins, multiple-table joins
- **NULL handling**

Each query is documented with in-line comments to explain the logic behind it.

## Project Structure

sql-portfolio/
├── .vscode/
│ └── settings.json # (Optional) SQLTools settings
├── projects/
│ ├── world_queries.sql # Exercises from the 'world' database
│ ├── euro2012.sql # Football statistics queries
├── tables/
│ ├── world.sql # SQL to create/populate the 'world' DB
├── .gitignore
└── README.md


## Setup

1. Ensure you have **MySQL** installed and running.
2. Use the `world.sql` and other `.sql` files to create and populate the databases.
3. Connect to your MySQL instance in VS Code using the **SQLTools** extension.

### Example SQLTools config (`.vscode/settings.json`):

```json
{
  "sqltools.connections": [
    {
      "name": "LocalSQL",
      "driver": "MySQL",
      "server": "localhost",
      "port": 3306,
      "username": "root",
      "database": "world"
    }
  ]
}
```

⚠️ Be sure to replace these details with your own MySQL credentials. Do not commit sensitive information to public repos.

How to Run Queries
Use SQLTools in VS Code:

Open .sql files

Select the query

Press Ctrl+E Ctrl+E to run against the connected database
