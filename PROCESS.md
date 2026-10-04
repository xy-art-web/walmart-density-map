# Process

## Tools

I used Gemini as an AI coding collaborator to assist with data processing, geographic projection calculations, and script generation. Specifically, Gemini helped implement the custom Albers Equal Area Conic projection formula (`albers_projection()`) in Python using NumPy, set up Matplotlib's `hexbin()` visualization, overlay geographic latitude/longitude gridlines, and draft initial project documentation.

## Kept

I kept the hexagonal binning (`hexbin()`) spatial aggregation method using a custom purple-to-blue colormap. Initially, plotting over 4,600 individual store locations as scatter points caused severe overplotting and visual clutter in densely populated metropolitan areas. Switching to hexagonal grid cells clearly highlights national store density corridors and regional retail concentrations while preserving background map readability.

## Rejected

I rejected using a traditional scatter plot with thousands of individual store dots. Standard scatter plots caused severe overplotting in major metropolitan areas, making the map look like a chaotic cluster of overlapping dots. I replaced it with hexagonal binning to represent local density cleanly.
