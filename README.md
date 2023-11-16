# Tanstack Demo

- [Official Docs](https://tanstack.com/table/v8/docs/adapters/react-table)
- [Official Github Examples](https://github.com/TanStack/table/tree/main/examples/react)

## First Steps

1. pull the repo
2. install dependencies
```shell
npm install
```
3. spin up the app
```shell
npm run dev
```

You should see the following page open in your browser:

![image](https://github.com/wegotpop/tanstack-demo/assets/90616460/b4ea42bb-f3ef-4852-a50d-5b8e72fcc9d4)

## Task 1 - Columns:

- remove the top 2 rows of extra headers
- combine the firstName & lastName columns into a single "Full Name" column
- hide the age if it's > 18 (adult) and just put "Adult" in each cell instead

## Task 2 - Table Features:

- implement sorting the table by clicking on a particular column header
  - [Example Code](https://github.com/TanStack/table/tree/main/examples/react/sorting)
- implement global search for the `GlobalSearch` component (currently this does nothing)
  - [Example Code](https://github.com/TanStack/table/blob/main/examples/react/filters/src/main.tsx)
