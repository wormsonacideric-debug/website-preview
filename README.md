# WORMS ON ACID branch preview

This repository publishes a selected branch of `wormsonacideric-debug/website-` to this repository's GitHub Pages site. It does not modify the source website or its `main` branch.

## Publish a branch

1. In this repository, open **Actions**.
2. Select **Publish branch preview**.
3. Choose **Run workflow** and enter a branch name from `wormsonacideric-debug/website-`.
4. Run it and wait for the deployment job to finish.
5. Open the Pages URL shown in the workflow run.

Each run replaces the preview with the selected branch. This is a shared preview, not a separate URL per branch. The workflow defaults to `perf/optimise-large-images`.

## One-time repository setting

In **Settings → Pages**, set the build and deployment source to **GitHub Actions** if it is not already selected.

Relative asset links are preserved because the site is published at the preview site's root. Any absolute links or domain-specific behaviour in the source branch may still point at production.
