<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0zb51t1k"/><path class="n8l86rbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conical-hat" /></template>
<style>
.i0zb51t1k {
  d: path("m3 14.5l9-10l9 10q-9 2.5-18 0Z");
}

.n8l86rbdw {
  d: path("M7.25 15.5q4.75 6.5 9.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
