# Nude-Images

A simple static website project served with Express.

## Overview

This repository contains a small web project with the following files:

- `index.html` — main website page.
- `index.js` — Express server serving static files.
- `package.json` — project metadata and dependency configuration.
- `Images/` — folder for image assets used by the site.

## Requirements

- Node.js 18+ (or a compatible Node.js version)
- npm

## Setup

```bash
cd /workspaces/Nude-Images
npm install
```

## Run the project

```bash
npm start
```

Then open your browser at `http://localhost:5000`.

## Project structure

- `index.js` starts an Express server.
- `express.static` serves the website files from the repository root.
- `index.html` is the entry point for visitors.

## Notes

- Do not commit `node_modules/` to GitHub. It can be rebuilt with `npm install`.
- The app listens on port `5000` by default.

## License

This project is released under the ISC license.
