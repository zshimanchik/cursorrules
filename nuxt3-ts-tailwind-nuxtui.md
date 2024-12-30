# Project Technology Stack and Preferences

This is a Nuxt 3 project that follows these technical guidelines:

Framework & Core:
- Nuxt 3 as the main framework
- TypeScript for type safety
- Vue 3 Composition API preferred over Options API

UI & Styling:
- Nuxt UI for component library
- Tailwind CSS for styling
- Avoid inline styles when possible
- Follow Nuxt UI design patterns and conventions

State Management & Utilities:
- Pinia for state management
- VueUse for composition utilities
- Prefer using 'npx nuxi@latest module add' for adding new modules and functionality

Code Style:
- Use TypeScript for all new files
- Prefer Composition API with <script setup lang="ts"> syntax
- Use proper type annotations
- Follow Vue 3 best practices
- Use ES6+ features
- Keep components single-responsibility
- Use composables for reusable logic
- For .vue files, maintain section order: <template>, <script>, <style>

File Structure:
- Follow Nuxt 3 directory structure conventions
- Keep components modular and reusable
- Use proper naming conventions (PascalCase for components, camelCase for files)

When suggesting code:
- Include TypeScript types
- Use Nuxt 3 built-in composables when applicable
- Leverage Nuxt UI components and utilities
- Implement proper error handling
- Consider performance implications 