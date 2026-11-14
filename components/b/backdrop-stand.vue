<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n_frlqb1j"/><path class="n-hhsg8tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backdrop-stand" /></template>
<style>
.n_frlqb1j {
  d: path("M2.5 21h3M4 21V4h16v17m-1.5 0h3");
}

.n-hhsg8tm {
  d: path("M7 4v12h10V4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
