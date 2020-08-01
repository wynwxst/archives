# Coronavirus (COVID-19) Dashboard

📈 [**Coronavirus (COVID-19) Dashboard**](https://he1ios.github.io/Covid19Dash/) shows the dynamics (the curvature of the graph) of Сoronavirus distribution per country.

### Main Functionality

The dashboard is still raw but it provides a basic functionality of displaying the global and per-country data charts.

Here is how the main functionality looks like:

![COVID-19 Dashboard Demo](./img/demo.gif)

## Data source and tech-stack

The dashboard is using [COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) as a data source.

Front-end wise I've tried to make it as simple as possible, therefore the dashboard is using a pure [React.js](https://reactjs.org/) (without `JSX` transpiler or `CreateReactApp` starter). To draw the chart I've used [Charts.js](https://www.chartjs.org/).

