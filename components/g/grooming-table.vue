<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o6haz77bt"/><path class="y-2frotgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grooming-table" /></template>
<style>
.o6haz77bt {
  d: path("M3 13h18m-9 0v7.5m-4 0h8m3-7.5V4h-6v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-2frotgu {
  d: path("M11 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
