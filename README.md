# Danbury Park Neighborhood Map

An interactive web application for exploring the Danbury Park neighborhood. Click on any house to see who lives there, or search by resident name to find their location on the map.

Created by **Dave Gilbert** for the Danbury Park community.

## Features

- **Interactive Map**: Click on any house marker to see resident information
- **Name Search**: Type a resident's name to instantly locate them on the map
- **Visual Feedback**: Subtle purple markers show all houses, with hover effects for easy navigation
- **Mobile Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **No Server Required**: Runs entirely in your browser with no backend needed

## Live Demo

Visit the live application: [https://whispersnowleopard.github.io/danbury/](https://whispersnowleopard.github.io/danbury/)

## How to Use

1. **Browse the Map**: Look for subtle purple dots marking each house location
2. **Click a House**: Click any marker to see who lives there
3. **Search by Name**: Type a resident's name in the search box to find and highlight their house
4. **Navigate**: Hover over markers to see addresses before clicking

## Technical Details

- Pure HTML/CSS/JavaScript (no frameworks required)
- Embedded SVG map with coordinate-based positioning
- GPS coordinates mapped to pixel positions with street-specific adjustments
- Client-side search and filtering
- LocalStorage not used - completely stateless

## Privacy Note

This tool is intended for use within the Danbury Park community. Please respect residents' privacy and use this information responsibly.

## Local Development

To run locally:
1. Clone this repository
2. Open `index.html` in any modern web browser
3. No build process or dependencies required

## For Developers

The code includes a configurable offset system for fine-tuning marker positions on stylized maps. See the `STREET_OFFSETS` section in the code for details on customizing positioning.

## Contributing

This is a community tool. If you notice incorrect information or have suggestions for improvements, please open an issue or submit a pull request.

## License

Created for the Danbury Park community.
