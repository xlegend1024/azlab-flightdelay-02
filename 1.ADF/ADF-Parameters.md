### ForEach and user parameters

settings
items
Select parameters 'fileurl'

```
@pipeline().parameters.fileurl
```

https://mtcsdataai.blob.core.windows.net/flight/airport-master/AirportMasterData.csv


## Copy multiple files to ADLS

Understand how to use parameters

### Piepeline Parameters

|name|Type|Value|
|--|--|--|
|fileurl|Array|```[{"source":{"url":"flight/batch-scoring/BatchScoringDataset.csv"},"destination":{"fileName":"batch-scoring/BatchScoringDataset.csv"}},{"source":{"url":"flight/carrier-master/CarrierMasterData.csv"},"destination":{"fileName":"carrier-master/CarrierMasterData.csv"}},{"source":{"url":"flight/flight-transactions/FlightDelaysWithAirportCodes-part1.csv"},"destination":{"fileName":"flight-transactions/FlightDelaysWithAirportCodes-part1.csv"}},{"source":{"url":"flight/flight-transactions/FlightDelaysWithAirportCodes-part2.csv"},"destination":{"fileName":"flight-transactions/FlightDelaysWithAirportCodes-part2.csv"}},{"source":{"url":"flight/flight-transactions/FlightDelaysWithAirportCodes-part3.csv"},"destination":{"fileName":"flight-transactions/FlightDelaysWithAirportCodes-part3.csv"}},{"source":{"url":"flight/weather-ref/AirportWeatherReferenceData.csv"},"destination":{"fileName":"weather-ref/AirportWeatherReferenceData.csv"}}]```|


