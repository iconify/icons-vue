<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.57 .57)scale(.96413)"><path class="jau5q0_ef"/><path class="cc7p1mlst"/><path class="xfrmy9ixf"/><path class="jg1o6lbvf"/><path class="a8slyv4ag"/><path class="wr2yq4bmo"/><path class="pmhyzbgbv"/><path class="nx0e1cy4s"/><ellipse class="r8srqky_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-plsql-package-body" /></template>
<style>
.a8slyv4ag {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M3.56 21.54h9.37v3.6H3.56z");
}

.cc7p1mlst {
  fill: var(--svg-color--efc75e, #efc75e);
  d: path("M13.36 2.04h4.32c.46 2.13.97 4.25 1.44 6.38H11.9q.74-3.18 1.46-6.38");
}

.jau5q0_ef {
  fill: var(--svg-color--f2e6c9, #f2e6c9);
  d: path("M7.12 2.05q3.12-.02 6.24 0L11.9 8.42H2.41l-.9-.01zm10.56 0h6.22l5.62 6.36q-1.8.02-3.6 0h-6.8c-.47-2.12-.98-4.24-1.44-6.37");
}

.jg1o6lbvf {
  fill: var(--svg-color--dbb551, #dbb551);
  d: path("M11.9 8.42h7.22v6.74l-.2.01h-6.75l-.26-.01z");
}

.nx0e1cy4s {
  fill: var(--svg-color--ffda44, #ffda44);
  d: path("M17.43 18.9a16 16 0 0 0 5.58.9a16 16 0 0 0 5.58-.9c1.4-.55 1.9-1.15 1.9-1.5v-2.67a8 8 0 0 1-1.57.81a17 17 0 0 1-5.9.98a17 17 0 0 1-5.92-.98a8 8 0 0 1-1.56-.8v2.66c0 .35.5.96 1.9 1.5");
}

.pmhyzbgbv {
  fill: var(--svg-color--red, red);
  d: path("M17.43 23.93a12 12 0 0 0 1.95.55a20 20 0 0 0 7.26 0a12 12 0 0 0 1.95-.55c1.4-.55 1.9-1.15 1.9-1.5v-2.54a8 8 0 0 1-1.27.62a18 18 0 0 1-6.2 1a18 18 0 0 1-6.2-1a8 8 0 0 1-1.27-.63v2.55c0 .35.49.95 1.88 1.5");
}

.r8srqky_w {
  cx: 23.01px;
  cy: 11.88px;
  fill: var(--svg-color--ffda44, #ffda44);
  rx: 7.47px;
  ry: 2.92px;
}

.wr2yq4bmo {
  fill: var(--svg-color--red, red);
  d: path("M23.01 29.96c4.13 0 7.48-1.31 7.48-2.92V24.9a8 8 0 0 1-1.16.57l-.11.05a18 18 0 0 1-6.2 1.01a18 18 0 0 1-6.2-1.01l-.12-.05a8 8 0 0 1-1.15-.57v2.13c0 1.61 3.34 2.92 7.46 2.92");
}

.xfrmy9ixf {
  fill: var(--svg-color--e7bf55, #e7bf55);
  d: path("M1.51 8.4q.45.03.9.02h9.49v6.73l.26.02h6.75l.2-.01q.02-3.38 0-6.74h6.8l3.6-.01v19.46h-28Z");
}

</style>
