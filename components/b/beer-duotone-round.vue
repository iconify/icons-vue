<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tg5ekskpo"/><path class="deev6eljl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:beer-duotone-round" /></template>
<style>
.deev6eljl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9v8a4 4 0 0 0 4 4h4a4 4 0 0 0 4-4V9m0 3h1a3 3 0 0 1 0 6h-1m-8-5v4m4-4v4M4 9c-2.667-4 3.333-8 6-4c2.667-4 8.667 0 6 4z");
}

.ft5dv1b6b {
  fill: none;
}

.tg5ekskpo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 9.287V17a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V9.287a4.8 4.8 0 0 1-.602-1.597c-.319-1.801.552-3.525 2.047-4.522c.951-.633 2.118-.942 3.256-.783A4.3 4.3 0 0 1 10 3.472a4.3 4.3 0 0 1 2.299-1.087c1.138-.159 2.305.15 3.256.783c1.495.997 2.366 2.721 2.047 4.522A4.8 4.8 0 0 1 17 9.287");
}

</style>
