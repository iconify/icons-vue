<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x-d3mlb0q"/><path class="khmh6acee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:figure-skater-spin" /></template>
<style>
.khmh6acee {
  d: path("M10.25 3.75L12 5l-1.75 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-d3mlb0q {
  d: path("M10.5 9H14v3.75L17 14a1.75 1.75 0 0 1 1.25 1.75V17H10.5Zm-1 11H19a2 2 0 0 0 2-2m-9-1v3m4.5-3v3m-13-3A9 9 0 0 1 12 5");
}

</style>
