# City Boundaries API of Azavea and how to use it #
Azavea's city boundaries API allows developers to retrieve the boundary of a specified city as a MultiPolygon GeoJson Feature. This API is useful for those looking to integrate geographical data into their projects.


[City Boundaries API](https://www.worldindata.com/api/Azavea-city-boundaries-api)

Worldindata's API marketplace aims to provide a comprehensive collection of third party APIs, making it easier for users to access and understand various types of data. By featuring a diverse range of APIs, the platform aims to provide a convenient one-stop-shop for developers seeking to incorporate various forms of information into their work.


## Needs, Industry, and Sectors ##

**Industry and Sectors**
- geospatial
- climate
- aviation
- travel
- booking and more

**Client Types**
- mapping and geospatial services
- travel
- aviation
- booking websites and more




## Parameters, Objects and JSON output ##
The GET /api/city/{pk}/boundary/ endpoint allows users to retrieve the boundary of a specified city as a MultiPolygon GeoJson Feature.

**Filter Parameters**
- pk


```
{
    "type": "Feature",
    "geometry": {
        "type": "MultiPolygon",
        "coordinates": [
            [
                [
                    [
                        0,
                        0
                    ]
                ]
            ]
        ]
    }
}

```
**Objects**
- type
- geometry
- coordinates

## Software Development Kit ##
Software Development Kits (SDKs) are available for the Azavea geojson city boundaries API in a variety of programming languages, including PHP, JavaScript, JAVA, Python, and Ruby.

### Legal disclaimer ###
Worldindata is not the owner of the data featured on its platform, but rather serves as a conduit between developers and data providers. We strive to make data in the world more user-friendly and accessible. As fans of the Azavea city boundaries API, we are excited to offer this valuable resource to our users. Please note that Worldindata is not responsible for the accuracy or reliability of the data provided through the API.


[Worldindata](https://www.worldindata.com)
