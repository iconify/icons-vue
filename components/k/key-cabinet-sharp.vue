<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nkgx4s2-g"/><circle class="prtzy8bxe"/><path class="nas-b8bjc"/><circle class="s_dqu5bpt"/><path class="xlr9k7beb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-cabinet-sharp" /></template>
<style>
.nas-b8bjc {
  d: path("M9 12.25v5.5h1.5");
}

.nkgx4s2-g {
  d: path("M3.75 2.75h16.5v18.5H3.75zm3 3.5h10.5");
}

.prtzy8bxe {
  cx: 9px;
  cy: 10.75px;
  r: 1.5px;
}

.s_dqu5bpt {
  cx: 15px;
  cy: 10.75px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlr9k7beb {
  d: path("M15 12.25v5.5h1.5");
}

</style>
