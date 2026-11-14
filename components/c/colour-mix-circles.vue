<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l5hr3qb8t"/><path class="dy1yp9btx"/><path class="x2wa61b0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-mix-circles" /></template>
<style>
.dy1yp9btx {
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.l5hr3qb8t {
  d: path("M6.5 9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2wa61b0h {
  d: path("M10 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
