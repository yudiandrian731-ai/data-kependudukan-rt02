# AI Editor Rules and Guidelines

This document outlines the technical stack and development conventions for the AI editor (Dyad) working on this project.

## Tech Stack Overview

*   **Framework:** React
*   **Language:** TypeScript (for type safety and maintainability).
*   **Routing:** React Router (for client-side navigation).
*   **Styling:** Tailwind CSS (used exclusively for all styling and responsiveness).
*   **Component Library:** shadcn/ui (for high-quality, accessible components built on Radix UI).
*   **Icons:** lucide-react (for all iconography).
*   **Structure:** Source code resides in `src/`. Pages are in `src/pages/` and reusable components are in `src/components/`.
*   **Design:** All designs must be responsive by default.

## Library Usage Rules

1.  **UI Components:** Always prioritize using components from the `shadcn/ui` library. If a specific component is needed but not available or requires significant modification, create a new, dedicated component file (`src/components/`). Do not modify existing `shadcn/ui` source files.
2.  **Styling:** Use Tailwind CSS classes exclusively for all styling, layout, and design decisions.
3.  **Icons:** Use icons imported from the `lucide-react` package.
4.  **Routing:** Use `react-router-dom` for defining and managing application routes, keeping the main routing configuration in `src/App.tsx`.
5.  **File Structure:** Every new component or hook must reside in its own small, focused file.