# d3 month heatmap

drawing only one month.

## demo
demo can be found [here](https://yalin.github.io/d3-month-heatmap/)

## challenge
In most of the examples, they made the heatmap as the year. Therefore, any month except January was drawn, leaving a left margin. Regardless of the month, when you take the minimum date to draw left-aligned, find the week of this date in the year, and subtract it from the other weeks; It's like it was scaled to start from 0.
