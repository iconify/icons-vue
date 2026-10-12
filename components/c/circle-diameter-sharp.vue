<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d993r-bho"/><path class="m85ry_-if"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circle-diameter-sharp" /></template>
<style>
.d993r-bho {
  d: path("M12 2.75a9.25 9.25 0 1 1 0 18.5a9.25 9.25 0 1 1 0-18.5");
}

.m85ry_-if {
  d: path("M5.75 12h12.5M8 9.75L5.75 12L8 14.25m8-4.5L18.25 12L16 14.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
