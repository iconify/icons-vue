<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e03z27b0p"/><path class="srf-vzl6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-maternity" /></template>
<style>
.e03z27b0p {
  d: path("M7.75 4.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM10 6.5v1.25M9 7.5c2 0 3.25 1 3.5 3c5.5 0 7.5 6.5 2.5 8.75c-1 .5-2 .5-2.5.5v1.75H8C7.75 18 6.75 14 7.25 11C7.5 9 8 7.75 9 7.5Z");
}

.srf-vzl6f {
  d: path("M9.75 11.5c0 1.75 1.25 2.75 3.25 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
