<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jv0st9g8g"/><path class="m-syn6bkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crop-rotation-sharp" /></template>
<style>
.jv0st9g8g {
  d: path("M4 12a8 8 0 0 1 13.66-5.66M18 2.75V6.5h-3.75M20 12a8 8 0 0 1-13.66 5.66M6 21.25V17.5h3.75M12 16v-4.5");
}

.m-syn6bkb {
  d: path("M12 13.5q.02-3.52-3.5-3.5q-.02 3.52 3.5 3.5Zm0-1.5q3.52.02 3.5-3.5q-3.52-.02-3.5 3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
