<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yrwb1lbkt"/><path class="qbivb1e5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-open" /></template>
<style>
.qbivb1e5q {
  d: path("M10 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7.5 0H4m16 0h1.5M3 2.75L4.25 4M21 2.75L19.75 4M3 11.75l1.25-1.25M21 11.75l-1.25-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrwb1lbkt {
  d: path("M6.5 2.5h11V12h-11Zm5.5 10V21m-4 0h8");
}

</style>
