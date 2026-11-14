<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rur0mzb4g"/><path class="bzfnoibwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forward-5" /></template>
<style>
.bzfnoibwe {
  d: path("m9 2.5l3 3l-3 3m4.5 2h-2.75l-.25 2.25c.5-.25 1-.25 1.5-.25c1 0 1.75.75 1.75 1.5c0 1-.75 1.5-1.75 1.5q-1.125 0-1.5-.75");
}

.rur0mzb4g {
  d: path("M18.495 9.25A7.5 7.5 0 1 1 12 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
