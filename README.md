# ESLint Types

TypeScript type definitions for the prolific JavaScript linting library, ESLint.
This project was created out of the need for types on a new
[feature](https://eslint.org/docs/latest/user-guide/configuring/configuration-files-new)
that hadn't made it to `@types/eslint` library at the time of development.

This project runs a `prepare` script on install to automatically generate `.d.ts` files
for the latest ESLint version. This is possible because of ESLint's thorough
JSDoc typing information.
