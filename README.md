# Lane Departure and Eye Tracking Visualizations

R Markdown code for STA 230 (Grinnell College, Fall 2023) that cleans, reshapes and plots two public data sets with ggplot2.

Files:
- lane_departure_eye_tracking.Rmd : main script. Visualization 1 totals left and right lane departures for each subject and drive in driving simulator data (drives.csv) and plots a histogram for each drive (RT1-RT4). Visualization 2 joins eye-tracking data (target.csv, cohort.csv) by subject and time, reshapes it to long format and plots each subject's proportion of looks over time with a loess curve, by noise condition and image type.
- lane_departure_eye_tracking.pdf : knitted PDF of the R Markdown file

Data:
- The three csv files are read from their course URLs in the code, so no local data is needed.

To run: knit lane_departure_eye_tracking.Rmd in R with ggplot2, dplyr and tidyr installed.
