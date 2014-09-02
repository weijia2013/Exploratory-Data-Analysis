# Week1 Quiz
## Q1 Principles of Analytic Graphics

1.  Show comparisons
2.  Show causality, mechanism, explanation
3.  Show multivariate data
4.  Integrate multiple modes of evidence
5.  Describe and document the evidence 
6.  Content is king

##Q2 Exploratory graphs in data analysis

1.  To understand data properties 
2.  To find patterns in data
3.  To suggest modelling strategies
4.  To "debug" analyses

## Characteristics of exploratory graphs

1.  They are made quickly
2.  A large number are made
3.  The goal is for personal understanding
4.  Axes/legends are generally cleaned up(later)
5.  Color/size are primarily used for information

##Q3 Base plot system

1.  Start with blank canvas and build up from there
2.  Start with plot function (or similar)
3.  Use annotation functions to add/modify (text, lines, points, axis)
4.  Convenient, mirrors how we think of building plots and analyzing data
5.  `Can't go back once plot has started`  (i.e. to adjust margins); need to plan in advance
6.  Difficult to "translate" to others once a new plot has been created (no graphical "language")
7.  Plot is just `a series of R commands`

##Q8 Graphics Devices in R

1.  On a Mac the screen device is launched with the `quartz()`
2.  On Windows the screen device is launched with `windows()`
3.  On Unix/Linux the screen device is launced with `x11()`

##Q4, Q5 Graphic File Devices

## Vector formats

1. pdf
2. svg
3. win.metafile
4. postscript

## Bitmap formats

1. png
2. jpeg
3. tiff
4. bmp

##Q6

Vector formats are good for line drawings and plots with solid colors using a modest number of points
Bitmap formats are good for plots with a large number of points, natural scenes or web-based plots

##Q9 Some Important Base Graphics Parameters

1.  `pch`: the plotting symbol (default is open circle)
2.  `lty`: the line type (default is solid line), can be dashed. dotted, etc.
3.  `lwd`: the line width, specified as an integer multiple
4.  `col`: the plotting color, specified as a number, string, or hex code; the colors() function gives you a vector of colors by name
5.  `xlab`: character string for the x-axis label
6.  `ylab`: character string for the y-axis label
7.  `las`: the orientation of the axis labels on the plot
8.  `bg`: the background color
9.  `mar`: the margin size
10.  `oma`: the outer margin size(default is 0 for all sides)
11.  `mfrow`: number of plots per row, column(plots are filled row-wise)
12.  `mfcol`: number of plots per row, column(plots are filled column-wise)


