Request for API access from <https://www.mytransport.sg/content/mytransport/home/dataMall/request-for-api.html>

Assuming `export accountkey="SECRET"`

# Deploy and run
```
go get
go build
accountkey=SECRET PORT=8080 UP_STAGE=production ./ltabus
curl 'localhost:8080/?id=07331'
```
# License

MIT

# Icon generator

Font is from https://dejavu-fonts.github.io/

## Related

* <https://github.com/cheeaun/arrivelah>
* <https://cheeaun.github.io/busrouter-sg/>
