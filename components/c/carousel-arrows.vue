<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-9o9hyeb"/><path class="fm_vy6x5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carousel-arrows" /></template>
<style>
.fm_vy6x5b {
  fill: currentColor;
  d: path("M6.75 12a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm4 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

.p-9o9hyeb {
  d: path("M4.25 9L2.5 12l1.75 3m15.5-6l1.75 3l-1.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
