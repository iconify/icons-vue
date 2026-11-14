<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bf1dmjbmi"/><path class="h9wvsabak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chicken-coop" /></template>
<style>
.bf1dmjbmi {
  d: path("M3.5 9.5L12 3l8.5 6.5V16h-17Z");
}

.h9wvsabak {
  d: path("M10 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-4 5v5m8-5l7.5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
