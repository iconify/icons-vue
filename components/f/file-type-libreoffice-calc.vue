<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGIqJReSyg" x1="4" x2="28" y1="31" y2="1" gradientUnits="userSpaceOnUse"><stop offset="0" class="jpdzn9bjm"/><stop offset="1" class="obgjkccbw"/></linearGradient></defs><g class="ywbk9fbil"><path fill="url(#SVGIqJReSyg)" transform="translate(2 2)scale(.875)" class="v6qbtcbjh"/><path class="y7nzi9tng"/><path class="ck4pcsb0s"/><path class="d3jbu4b9s"/><path class="j033robti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-libreoffice-calc" /></template>
<style>
.ck4pcsb0s {
  fill-opacity: var(--svg-fill-opacity--0-201, 0.201);
  d: path("M19.5 2h1.225l6.65 6.65v1.225z");
}

.d3jbu4b9s {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M9.875 13.375A.873.873 0 0 0 9 14.25v6.125c0 .485.39.875.875.875h5.25v-.875h-1.75V19.5h1.75v-.875h-1.75v-.875h7v-3.5a.873.873 0 0 0-.875-.875zm0 .875H12.5v.875H9.875zm3.5 0H16v.875h-2.625zm3.5 0H19.5v.875h-2.625zm-7 1.75H12.5v.875H9.875zm3.5 0H16v.875h-2.625zm3.5 0H19.5v.875h-2.625zm-7 1.75H12.5v.875H9.875zm0 1.75H12.5v.875H9.875z");
}

.j033robti {
  fill: var(--svg-color--b4f48b, #b4f48b);
  d: path("M16 17.75a.873.873 0 0 0-.875.875V23c0 .485.39.875.875.875h6.125c.485 0 .875-.39.875-.875v-4.375a.873.873 0 0 0-.875-.875zm1.75.875h.875V23h-.875zM16 19.5h.875V23H16zm5.25.875h.875V23h-.875zm-1.75.875h.875V23H19.5z");
}

.jpdzn9bjm {
  stop-color: var(--svg-color--007c3c, #007c3c);
}

.obgjkccbw {
  stop-color: var(--svg-color--78fc4e, #78fc4e);
}

.v6qbtcbjh {
  d: path("M7 0C4.784 0 3 1.784 3 4v24c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4V12L17 0zm13 0l9 9V0z");
}

.y7nzi9tng {
  fill-opacity: var(--svg-fill-opacity--0-199, 0.199);
  d: path("M4.625 25.625v.875c0 1.939 1.561 3.5 3.5 3.5h15.75c1.939 0 3.5-1.561 3.5-3.5v-.875c0 1.939-1.561 3.5-3.5 3.5H8.125a3.49 3.49 0 0 1-3.5-3.5");
}

.ywbk9fbil {
  fill-rule: evenodd;
  stroke-linecap: square;
}

</style>
