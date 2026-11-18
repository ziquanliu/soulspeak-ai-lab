# Soulspeak AI Lab

A static research lab website built for GitHub Pages. The homepage includes the lab vision, three research questions, selected publications and contact details. HTML, CSS, artwork and web fonts are all included. Editing or publishing the site requires no installation or build command.

## Publish on GitHub Pages

1. Extract `soulspeak-ai-lab.zip` on your computer.
2. Create a public GitHub repository, for example `soulspeak-ai-lab`. On its **Code** page, choose **uploading an existing file** for an empty repository, or **Add file → Upload files**.
3. Drag the **contents of the extracted folder** into the upload area. Include the entire `assets` folder. Commit the files to `main`. Check that `index.html` appears at the top level on the repository’s **Code** page.
4. In **Settings → Pages**, under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, and click **Save**.
5. When deployment finishes, use **Visit site** on the Pages settings screen. Future commits to this branch update the website.

The archive includes an optional `.nojekyll` file for plain static hosting. All required site files have visible names. The same files work at an account homepage or under a project repository name.

[GitHub Pages publishing guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) · [GitHub file upload guide](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

## Edit or preview

- Edit `index.html` to change the vision, research questions, publications or contact information. Each publication is one list item inside the section with `id="publications"`.
- Edit `styles.css` to change the colours, layout or type. The colour variables are at the top. The print effect uses the `.printed` class and the inline SVG filter named `ink` in `index.html`.
- The artwork is in `assets/art/`. The harmonograph traces two damped oscillations with a 3:2 frequency ratio.
- To preview locally with Python 3, run `python3 -m http.server 8000` in the extracted directory and open <http://localhost:8000/>. The site uses relative asset paths and requires no JavaScript.

## Sources and font licences

The profile and selected work come from [Ziquan Liu’s academic website](https://sites.google.com/view/ziquanliu). The contact email is listed on his [QMUL research profile](https://www.seresearch.qmul.ac.uk/cmai/people/zliu/). Publication titles on the site link to the papers.

Display typography uses [Geist Serif Regular](https://github.com/vercel/geist-font). Body typography uses [Source Serif 4 Regular](https://github.com/adobe-fonts/source-serif). Both web fonts are bundled unmodified under the SIL Open Font License 1.1. Keep the accompanying [Geist licence](assets/fonts/Geist-OFL.txt) and [Source Serif licence](assets/fonts/SourceSerif-OFL.txt) with the font files.
