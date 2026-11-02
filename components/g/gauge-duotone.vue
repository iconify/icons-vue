<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gievz-bbr"/><path class="os8-7k32y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gauge-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gievz-bbr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.515 13a8.487 8.487 0 1 1 16.973 0a8.486 8.486 0 1 1-16.973 0");
}

.os8-7k32y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19a8.485 8.485 0 1 1 12 0m-6-6l3-3");
}

</style>
