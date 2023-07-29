# [Personal Portfolio](https://yubinkarki.com.np)

```
Vite project with React.
Tailwind CSS used for styling.
```

Process to build and push to a separate branch:

- `npm run build`
- `git add dist -f`
- `git commit -m "Message"`
- `git subtree push --prefix dist origin branchname`

Process to create new empty branch:

- `git switch --orphan <new branch>`
- `git commit --allow-empty -m "Initial commit on orphan branch"`
- `git push -u origin <new branch>`
