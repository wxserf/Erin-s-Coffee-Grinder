# Erin's Coffee Grinder

## Overview
Erin's Coffee Grinder is a web-based blueprint analyzer that processes automation blueprints and generates detailed specifications. This project has been modularized for easier maintenance and team collaboration.

## Project Structure
- `src/index.html`: Main HTML file referencing external CSS and JS.
- `src/styles/main.css`: Stylesheet extracted from original single-file app.
- `src/scripts/main.js`: Main JavaScript logic for UI and blueprint processing.
- `src/scripts/worker.js`: Web worker script for blueprint processing.
- `.gitignore`: Specifies files and folders to ignore in Git.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.)
- Optional: Node.js and npm for running local servers and build scripts.

### Running Locally
You can serve the `src` directory using a simple HTTP server:

#### Using Python 3
```bash
python -m http.server 8080 --directory src
```

#### Using Node.js (with `serve` package)
```bash
npx serve src -p 8080
```

Then open your browser at `http://localhost:8080`.

### Development
- Edit source files in `src/`.
- The app will load the modularized CSS and JS files.

### Building for Distribution
(To be implemented) A build script will combine all files into a single distributable HTML file.

## Contributing
Please see `CONTRIBUTING.md` for guidelines.

## License
This project is licensed under the MIT License.
