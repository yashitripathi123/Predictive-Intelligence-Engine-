# Database Integration

## Overview

The Predictive Intelligence Engine uses database storage as part of its data processing and management architecture.

## Database Technologies

The project technology stack includes:

- PostgreSQL
- SQLite

PostgreSQL is suitable for structured application and analytical data, while SQLite can be used for lightweight local or development storage.

## Database Role

The database layer can support:

- Storing structured data
- Managing application data
- Maintaining processed information
- Supporting data retrieval for analysis
- Providing data to the intelligence and prediction layers

## Data Flow

Data Sources → Data Processing → Database Storage → AI/ML Processing → Predictions and Insights

## Production Database

The deployment architecture specifies Neon PostgreSQL as the database deployment platform.

## Integration

The database layer works with the backend so that application data can be stored and retrieved when required by the predictive intelligence workflow.
