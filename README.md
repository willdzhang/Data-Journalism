# Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

The data set is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml)

## D3

![4-scatter](Images/4-scatter.jpg)

Create a scatter plot between two data variables.

Using D3, create a scatter plot that represents each state with circle elements.

* Include state abbreviations in the circles.

* Create and situate axes and labels to the left and bottom of the chart.

* Note: use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in your web browser.

- - -

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

Place additional labels in the scatter plot and give them click events so users can decide which data to display. Animate the transitions for the circles' locations as well as the range of axes.

* Bind all of the CSV data to the circles.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to the circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.

![8-tooltip](Images/8-tooltip.gif)

* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how you should implement tooltips with d3-tip.

- - -
