charts-theme-highcharts
=======================

A HighCharts Solution of [Charts](https://github.com/turingou/charts).

### Installation
````
$ npm install charts-theme-highcharts
````
### Example
Make sure your Charts server is running and visit:

#### Embed Mode
```
http:/localhost:3001/highcharts/500x350/%7B%22title%22%3Afalse%2C%22xAxis%22%3A%7B%22categories%22%3A%5B%222014-05-13%22%2C%222014-05-14%22%2C%222014-05-15%22%2C%222014-05-16%22%2C%222014-05-17%22%2C%222014-05-18%22%2C%222014-05-19%22%2C%222014-05-20%22%2C%222014-05-21%22%2C%222014-05-22%22%5D%2C%22labels%22%3A%7B%22rotation%22%3A-45%2C%22x%22%3A-20%2C%22y%22%3A40%7D%7D%2C%22yAxis%22%3A%7B%22title%22%3A%7B%22enabled%22%3Afalse%7D%7D%2C%22credits%22%3A%7B%22text%22%3A%22source%22%2C%22href%22%3A%22http%3A%5C%2F%5C%2Fwww.example.com%22%7D%2C%22series%22%3A%5B%7B%22name%22%3A%225.0.8.1%22%2C%22data%22%3A%5B236110%2C234280%2C233026%2C252196%2C278302%2C255967%2C117911%2C116971%2C118783%2C120074%5D%7D%2C%7B%22name%22%3A%225.0.9.7002%22%2C%22data%22%3A%5B212028%2C211060%2C205610%2C223100%2C231464%2C202436%2C105216%2C103498%2C103073%2C104791%5D%7D%5D%7D
```
#### Debug Mode
```
http:/localhost:3001/highcharts/500x350/%7B%22title%22%3Afalse%2C%22xAxis%22%3A%7B%22categories%22%3A%5B%222014-05-13%22%2C%222014-05-14%22%2C%222014-05-15%22%2C%222014-05-16%22%2C%222014-05-17%22%2C%222014-05-18%22%2C%222014-05-19%22%2C%222014-05-20%22%2C%222014-05-21%22%2C%222014-05-22%22%5D%2C%22labels%22%3A%7B%22rotation%22%3A-45%2C%22x%22%3A-20%2C%22y%22%3A40%7D%7D%2C%22yAxis%22%3A%7B%22title%22%3A%7B%22enabled%22%3Afalse%7D%7D%2C%22credits%22%3A%7B%22text%22%3A%22source%22%2C%22href%22%3A%22http%3A%5C%2F%5C%2Fwww.example.com%22%7D%2C%22series%22%3A%5B%7B%22name%22%3A%225.0.8.1%22%2C%22data%22%3A%5B236110%2C234280%2C233026%2C252196%2C278302%2C255967%2C117911%2C116971%2C118783%2C120074%5D%7D%2C%7B%22name%22%3A%225.0.9.7002%22%2C%22data%22%3A%5B212028%2C211060%2C205610%2C223100%2C231464%2C202436%2C105216%2C103498%2C103073%2C104791%5D%7D%5D%7D?preview=true
```
**TIPS:** `1x1` means auto-width and auto-height.Actually it was not implemented, We'll add it soon.

Data should be urlencoded. The raw data like this:
```
{
    "title": false,
    "xAxis": {
        "categories": ["2014-05-13", "2014-05-14", "2014-05-15", "2014-05-16", "2014-05-17", "2014-05-18", "2014-05-19", "2014-05-20", "2014-05-21", "2014-05-22"],
        "labels": {
            "rotation": -45,
            "x": -20,
            "y": 40
        }
    },
    "yAxis": {
        "title": {
            "enabled": false
        }
    },
    "credits": {
        "text": "source",
        "href": "http:\/\/www.example.com"
    },
    "series": [{
        "name": "5.0.8.1",
        "data": [236110, 234280, 233026, 252196, 278302, 255967, 117911, 116971, 118783, 120074]
    }, {
        "name": "5.0.9.7002",
        "data": [212028, 211060, 205610, 223100, 231464, 202436, 105216, 103498, 103073, 104791]
    }]
}
```

### Contributing
- Fork this repo
- Clone your repo
- Install dependencies
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Open a pull request, and enjoy <3

### MIT license
Copyright (c) 2014 wenzhao823 &lt;wenzhao823@gmail.com&gt;

### MIT license
Copyright (c) 2014 wenzhao823 &lt;wenzhao823@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the &quot;Software&quot;), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED &quot;AS IS&quot;, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
