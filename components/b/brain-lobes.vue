<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0xq7g9nz"/><path class="d34mslbpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brain-lobes" /></template>
<style>
.d34mslbpq {
  d: path("M11 4c-1.5 4 1.5 9-1 14.75M17 4.5c-2 3.5 1 7.5-1 12");
}

.g0xq7g9nz {
  d: path("M5.5 16.5A3.25 3.25 0 0 1 3.25 11a3.25 3.25 0 0 1 2.5-5.5A3 3 0 0 1 11 4a3.5 3.5 0 0 1 6 .5a3 3 0 0 1 3.25 4a3 3 0 0 1-.75 5.5a3 3 0 0 1-3.5 2.5a7 7 0 0 1-10.5 0ZM14 18l1 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
