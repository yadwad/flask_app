KGI Consulting
Load CSV data into Postgresql

CREATE TABLE IF NOT EXISTS data (
fields_state_abbr VARCHAR(6) NULL,
fields_state_fips VARCHAR(6) NULL,
fields_place_fips VARCHAR(6) NULL,
fields_stpl_fips VARCHAR(6) NULL,
fields_city_name VARCHAR(6) NULL,
fields_metric_name VARCHAR(6) NULL,
fields_metric_number VARCHAR(6) NULL,
fields_group_name VARCHAR(6) NULL,
fields_group_number VARCHAR(6) NULL,
fields_num VARCHAR(6) NULL,
fields_denom VARCHAR(6) NULL,
fields_est VARCHAR(6) NULL,
fields_lci VARCHAR(6) NULL,
fields_uci VARCHAR(6) NULL,
fields_county_indicator VARCHAR(6) NULL,
fields_educ_indicator VARCHAR(6) NULL,
fields_multiplier_indicator VARCHAR(6) NULL,
fields_data_yr_type VARCHAR(6) NULL,
fields_geo_level VARCHAR(6) NULL,
fields_date_export VARCHAR(4) NULL,
rows_state_abbr VARCHAR(2) NULL,
rows_state_fips INT NULL,
rows_place_fips INT NULL,
rows_stpl_fips INT NULL,
rows_city_name VARCHAR(26) NULL,
rows_metric_name VARCHAR(11) NULL,
rows_metric_number INT NULL,
rows_group_name VARCHAR(16) NULL,
rows_group_number INT NULL,
rows_num INT NULL,
rows_denom INT NULL,
rows_est FLOAT NULL,
rows_lci INT NULL,
rows_uci INT NULL,
rows_county_indicator INT NULL,
rows_educ_indicator INT NULL,
rows_multiplier_indicator INT NULL,
rows_data_yr_type VARCHAR(9) NULL,
rows_geo_level VARCHAR(4) NULL,
rows_date_export VARCHAR(20) NULL
);
