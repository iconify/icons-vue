<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nuygbdb3o"/><path class="j9obalb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earwig" /></template>
<style>
.j9obalb7j {
  d: path("M9.5 7h5v10h-5Zm2 10q-4 2-1 4.5m2-4.5q4 2 1 4.5m-4-9.5h5m-5-2.5L6.5 8m3 6.5l-3 1.5m8-6.5l3-1.5m-3 6.5l3 1.5");
}

.nuygbdb3o {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
