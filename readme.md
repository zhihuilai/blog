# blog

This repository stores my blog's markdown file. Instead of using github pages for static services, it uses Tencent cloud functions (scf) for hosting. When the commit hook is triggered, drone ci will automatically sync the latest blog to the Tencent Cloud MySQL database so you can access the latest posts.

If you are interested, click [zhihui.momentfly.com](https://zhihui.momentfly.com) to visit my blog.
