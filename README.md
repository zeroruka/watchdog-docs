# Watchdog API Documentation

This repository contains the codebase for the Watchdog API documentation website. The website is built using Next.js, a popular React framework, and styled with Tailwind CSS, a utility-first CSS framework. The documentation content is written in MDX, a format that lets you write JSX in your Markdown documents.

## Features

- Global Search: The website includes a global search feature powered by the `FlexSearch` library. The search feature works out of the box by automatically scanning your documentation pages to build its index. You can adjust the search parameters by editing the `/src/mdx/search.mjs` file.

- Dark Mode: The website supports dark mode out of the box, thanks to the `next-themes` library.

- Syntax Highlighting: The website uses `shiki` for syntax highlighting in code blocks.

- Responsive: The website is fully responsive and works well on various screen sizes.

## Getting Started

To get started with this codebase, first install the npm dependencies:

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

## Customizing

You can start customizing the website by modifying the files in the /src folder. The site will auto-update as you edit these files.

## License

This site template is a commercial product and is licensed under the [Tailwind UI license](https://tailwindui.com/license).
