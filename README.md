# Modify SWA calendar files
This file-action triggered workflow modifies Southwest Airlines calendar (ICS) files to fit my needs. 
![workflow](https://github.com/woodwerk/alfred_modifySWA/blob/master/modify%20SWA%20ICS.png)

The ICS files from the SWA website contains all the crucial information for your flights.  I thought it could be presented much better particularly for viewing on mobile devices.

I wanted to rearrange and streamline the information to make the event title show just the flight numbers (e.g., SWA: 5956/5694), have the location be the start and end airport codes (e.g., ABQ to SLC), include one day and 2 hour alerts and also edit the notes field to contain just the trip itinerary.

The file-action feeds the files to an AppleScript that handles all the text manipulation and saves the updated ICS file(s). Double-click the revised ICS files to add them to your calendar. Now the compact view of the event show just the most critical information - flights, cities and times. Better yet on the calendar or Fantastical watch complication prominently shows the flight numbers so you can easily check gate information on the monitors in the terminal.

![watch](https://github.com/woodwerk/alfred_modifySWA/blob/master/watch.PNG)

This [PDF](https://github.com/woodwerk/alfred_modifySWA/blob/master/Modify%20SWA%20ICS%20files.pdf) provides more about how the workflow operates and the AppleScript code that does the work.
