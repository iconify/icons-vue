<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ts7_libxb"/><path class="jhhmu8bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:force-field" /></template>
<style>
.jhhmu8bph {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ts7_libxb {
  d: path("M8.465 7.787a5.5 5.5 0 0 1 7.07 0m0 8.426a5.5 5.5 0 0 1-7.07 0M5.459 5.459a9.25 9.25 0 0 1 13.082 0m0 13.082a9.25 9.25 0 0 1-13.082 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
