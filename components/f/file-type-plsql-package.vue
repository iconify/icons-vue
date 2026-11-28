<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.1 .1)scale(.96413)"><path class="s_veg9vwk"/><path class="krcjany6l"/><path class="zhu_vebed"/><path class="zd9uehbvw"/><path class="rr3hlrbqy"/><path class="gtvap5njx"/><path class="a3yjb6bqh"/><ellipse class="nwj-0tnfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-plsql-package" /></template>
<style>
.a3yjb6bqh {
  fill: var(--svg-color--red, red);
  d: path("M23.5 31c4.13 0 7.47-1.3 7.47-2.92v-2.13a8 8 0 0 1-1.15.57l-.12.05a18 18 0 0 1-6.2 1.01a18 18 0 0 1-6.2-1.01l-.11-.05a8 8 0 0 1-1.16-.57v2.13c0 1.61 3.34 2.92 7.47 2.92");
}

.gtvap5njx {
  fill: var(--svg-color--red, red);
  d: path("M17.92 19.94a16 16 0 0 0 5.58.9a16 16 0 0 0 5.58-.9c1.4-.55 1.9-1.15 1.9-1.5v-2.66a8 8 0 0 1-1.57.8a17 17 0 0 1-5.91.98a17 17 0 0 1-5.9-.98a8 8 0 0 1-1.57-.8v2.66c0 .35.5.96 1.9 1.5m0 5.03a12 12 0 0 0 1.94.56a20 20 0 0 0 7.26 0a12 12 0 0 0 1.95-.56c1.4-.54 1.9-1.15 1.9-1.5v-2.54a8 8 0 0 1-1.28.62a18 18 0 0 1-6.2 1a18 18 0 0 1-6.2-1a8 8 0 0 1-1.27-.62v2.54c0 .35.5.95 1.9 1.5");
}

.krcjany6l {
  fill: var(--svg-color--efc75e, #efc75e);
  d: path("M13.85 3.09h4.31l1.45 6.37h-7.22z");
}

.nwj-0tnfr {
  cx: 23.5px;
  cy: 12.92px;
  fill: var(--svg-color--red, red);
  rx: 7.47px;
  ry: 2.92px;
}

.rr3hlrbqy {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M4.04 22.58h9.37v3.6H4.04z");
}

.s_veg9vwk {
  fill: var(--svg-color--f2e6c9, #f2e6c9);
  d: path("M7.61 3.1c2.08-.03 4.16 0 6.24-.02l-1.46 6.38H2.9q-.45.01-.9-.01zm10.55 0h6.22Q27.2 6.26 30 9.45l-3.6.01h-6.8z");
}

.zd9uehbvw {
  fill: var(--svg-color--dbb551, #dbb551);
  d: path("M12.4 9.46h7.2q.02 3.38 0 6.74l-.2.02h-6.74l-.26-.02z");
}

.zhu_vebed {
  fill: var(--svg-color--e7bf55, #e7bf55);
  d: path("m2 9.45l.9.01h9.5v6.74l.25.01h6.75l.2-.01q.02-3.38 0-6.74h6.8q1.8.01 3.6-.01V28.9H2z");
}

</style>
