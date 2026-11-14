<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ia54snzqy"/><path class="h9jfe3euv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fishing-lure" /></template>
<style>
.h9jfe3euv {
  d: path("M5.5 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM8 13v3.5a1.75 1.75 0 0 0 3.5 0m2.5-4V16a1.75 1.75 0 0 0 3.5 0");
}

.ia54snzqy {
  d: path("M3 9.5C5 6 13 5.5 18 8l3-1.5v6L18 11c-5 2.5-13 2-15-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
