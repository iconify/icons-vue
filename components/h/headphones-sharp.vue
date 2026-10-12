<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kslmxf1wp"/><path class="msb4-ibai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:headphones-sharp" /></template>
<style>
.kslmxf1wp {
  d: path("M3.75 13.25h4.5v7h-4.5zm12 0h4.5v7h-4.5z");
}

.msb4-ibai {
  d: path("M3.75 14.25V12a8.25 8.25 0 0 1 16.5 0v2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
