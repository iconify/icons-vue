<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tdo0-wb3y"/><path class="i5ko_-b0p"/><path class="i1fons8-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contact-agent" /></template>
<style>
.i1fons8-r {
  d: path("M10.75 14.5v-2.25h2.5v2.25m1.5-5.75v-2");
}

.i5ko_-b0p {
  d: path("M7.5 10.5L12 6l4.5 4.5v4h-9Z");
}

.tdo0-wb3y {
  d: path("M2.5 5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v10a2.5 2.5 0 0 1-2.5 2.5h-8L6.5 21v-3.5H5A2.5 2.5 0 0 1 2.5 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
