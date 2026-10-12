<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v3-6e0bxg"/><path class="m99jthbbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lake-sharp" /></template>
<style>
.m99jthbbb {
  d: path("M6.75 14.75L8 13.917l1.25.833l1.25.833l1.25-.833m-.75 3l1.25-.833l1.25.833l1.25.833L16 17.75M5.75 9.5l6.25-6l6.25 6");
}

.v3-6e0bxg {
  d: path("M2.75 16.25a9.25 5 0 1 0 18.5 0a9.25 5 0 1 0-18.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
