# Hanzi Path

This repository is ready for direct GitHub Pages deployment. It does not require Node.js, an app framework, a build command, or GitHub Actions.

## Publish from `main/docs`

1. Upload the contents of this folder to the `main` branch of a GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the **main** branch and the **/docs** folder.
6. Click **Save**.

GitHub will publish the site at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Site files

Everything GitHub Pages needs is already inside `docs/`. The site uses relative asset paths, so it works under any repository name. The `.nojekyll` file is required because the exported assets are stored in a directory beginning with an underscore.

Student progress is saved only in the student's browser. No login or server is required.
