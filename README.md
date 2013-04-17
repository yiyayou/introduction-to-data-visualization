introduction-to-data-visualization
==================================

#Day 1: Javascript overview

## primitive data types:
- number
- string
- boolean
- arrays
- objects

## numbers:
```javascript
var intNumber = 8; // integers
3.14 // floats
```

## string:
```javascript
var obviously = "Pizza is awesome."; // you can tell because there are quotes around the string
```

## boolean:
```javascript
var thisIsTrue = true;
var thisisFalse = false;
```

## arrays:
```javascript
var favoriteFoods = ["cheese pizza", "wood-fired pizza", "curry pizza", "smoked salmon pizza", "pepperoni pizza"];
```
## objects:
```javascript
var pizza = {
  cheese: "mozzarela",
  sauce: "tomato",
  toppings: ["pepperoni", "olives", "green pepper"]
};
```

# GitHub overview:
- Log in, then fork this repository.
- Now, you can click on files in the list, then click edit.
- Changes will show up at your-username.github.io/introduction-to-data-visualization

# Today's workshop challenge:
- Review the code used to create the line-chart example.
- Familiarize yourself with the [Chart.js documentation](http://www.chartjs.org/docs/).
- Create a pie chart using the following data:
```javascript
var data = [
  {
    value: 30,
    color:"#F38630"
  },
  {
    value : 50,
    color : "#E0E4CC"
  },
  {
    value : 100,
    color : "#69D2E7"
  }     
]
```
- Save the pie chart in the pie-chart.html file.

# For Thursday:
- Find a real data set. Some examples can be found at data.seattle.gov, data.gov, datahub.io, and elsewhere.
- Use this data set you've found to create any type of chart that Chart.js is capable of creating. Reference the [Chart.js documentation](http://www.chartjs.org/docs/).
- Save this new chart in the day2.html file.
- Find at least one example of an awesome data visualization.