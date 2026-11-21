<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGcZyoTdci" x1="8.1" x2="17.4" y1="8.1" y2="16" gradientUnits="userSpaceOnUse"><stop offset="0" class="smkeq5bnj"/><stop offset="1" class="p65kv2v4k"/></linearGradient><linearGradient id="SVGE9KQWcSk" x1="20.9" x2="17.6" y1="20.9" y2="16.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="wnl8esb6h"/><stop offset="1" class="oe9pdrcad"/></linearGradient><radialGradient id="SVGrLfiACAp" gradientTransform="matrix(0 -.059 -.259 0 20.3 26.8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="e2wn3nbsm"/><stop offset="1" class="n3udgr6an"/></radialGradient></defs><path fill="url(#SVGrLfiACAp)" class="dzinwrbup"/><path class="nuj32bckg"/><path fill="url(#SVGcZyoTdci)" class="yy9_f9biy"/><path fill="url(#SVGE9KQWcSk)" class="kpca96t1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cython" /></template>
<style>
.dzinwrbup {
  d: path("M21 25.9c0 .5-2.2.9-4.9.9s-4.8-.4-4.8-.9s2.15-1 4.8-1s4.9.45 4.9 1");
}

.e2wn3nbsm {
  stop-color: var(--svg-color--b8b8b8, #b8b8b8);
  stop-opacity: 0.22;
}

.kpca96t1h {
  d: path("M21.37 11.87v1.79a2.6 2.6 0 0 1-2.51 2.55h-4.01a2.05 2.05 0 0 0-2.01 2.03v3.83c0 1.1.94 1.73 2 2.04a6.7 6.7 0 0 0 4.01 0c1.02-.29 2.02-.88 2.02-2.04v-1.53h-4.01v-.5h6.02c1.17 0 1.6-.83 2-2.05a7 7 0 0 0 0-4.08c-.3-1.16-.83-2.04-2-2.04Zm-2.26 9.7a.77.77 0 1 1-.75.76a.76.76 0 0 1 .75-.77");
}

.n3udgr6an {
  stop-color: var(--svg-color--7f7f7f, #7f7f7f);
  stop-opacity: 0;
}

.nuj32bckg {
  fill: var(--svg-color--646464, #646464);
  d: path("M16.55 2.74a15 15 0 0 0-10.7 3.88A12 12 0 0 0 2 15.6a13.2 13.2 0 0 0 3.56 9.43q3.93 4.22 10.9 4.23q7.07 0 11.07-4.23a13 13 0 0 0 1.83-2.38h-5.44q-2.1 3.9-7.34 3.95a7.6 7.6 0 0 1-7-3.7a13.6 13.6 0 0 1-1.84-7.3q0-9.56 8.74-9.97q4.73.17 6.98 3.35a9 9 0 0 1 .76 1.25H30a12 12 0 0 0-2.68-3.61a15.2 15.2 0 0 0-10.77-3.88");
}

.oe9pdrcad {
  stop-color: var(--svg-color--ffe873, #ffe873);
}

.p65kv2v4k {
  stop-color: var(--svg-color--306998, #306998);
}

.smkeq5bnj {
  stop-color: var(--svg-color--5a9fd4, #5a9fd4);
}

.wnl8esb6h {
  stop-color: var(--svg-color--ffd43b, #ffd43b);
}

.yy9_f9biy {
  d: path("M16.8 7.6a12 12 0 0 0-1.96.14c-1.7.3-2.01.93-2.01 2.09v1.53h4.02v.51h-5.52a2.5 2.5 0 0 0-2.51 2.04a7.5 7.5 0 0 0 0 4.08c.29 1.19.97 2.04 2.13 2.04h1.38V18.2a2.55 2.55 0 0 1 2.5-2.5h4.02a2 2 0 0 0 2.01-2.04V9.8a2.24 2.24 0 0 0-2-2.06a13 13 0 0 0-2.1-.16M14.6 8.81a.77.77 0 1 1-.76.77a.76.76 0 0 1 .75-.77");
}

</style>
