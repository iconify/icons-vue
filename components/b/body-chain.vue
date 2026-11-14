<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zoej7biec"/><path class="o2xelwb3o"/><path class="tjs7_ob2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-chain" /></template>
<style>
.o2xelwb3o {
  d: path("M8.25 11.5a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

.tjs7_ob2s {
  d: path("M11.25 11.5a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zoej7biec {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h13.5c0-4-.75-7-.5-8l2.25-5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3");
}

</style>
