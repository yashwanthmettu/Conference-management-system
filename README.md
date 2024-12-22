This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, create a database in MySQL with the name `axr4477_cms`:

```sql
CREATE DATABASE axr4477_cms;
```

Then, load the `axr4477_cms_localhost.sql` file included in the folder:

```bash
mysql -u your_username -p axr4477_cms < path/to/axr4477_cms_localhost---.sql
```

Replace `your_username` with your MySQL username and `path/to/axr4477_cms_localhost---.sql` with the actual path to the SQL file.

Next, install the dependencies:

```bash
npm install
```

Build the project:

```bash
npm run build
```

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

To start the production server:

```bash
npm run start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


