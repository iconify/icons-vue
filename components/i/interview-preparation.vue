<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e1rz5sb8w"/><path class="d3rpwignn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-preparation" /></template>
<style>
.d3rpwignn {
  d: path("M10.75 15.5h2.5v6h-2.5Zm-1-8.75h4.5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H11.5L10 12v-1.25h-.25a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1Z");
}

.e1rz5sb8w {
  d: path("M5.75 8.75a6.25 6.75 0 1 0 12.5 0a6.25 6.75 0 1 0-12.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
