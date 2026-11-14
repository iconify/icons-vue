<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nuygbdb3o"/><path class="ey1lr0b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beanie-kids" /></template>
<style>
.ey1lr0b3h {
  d: path("M5 14c0-4.75 3-7 7-7s7 2.25 7 7M3.5 14h17v6.5h-17Zm4.25 0v6.5M12 14v6.5m4.25-6.5v6.5");
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
