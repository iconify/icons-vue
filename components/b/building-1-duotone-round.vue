<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tpz5dabmt"/><path class="jlzwcxbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jlzwcxbjk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M9 20v-4c0-1.28.36-2.36 1-3l2-2a2.83 2.83 0 0 1 4 0l2 2c.64.64 1 1.72 1 3v4m-7-9V7a3 3 0 0 0-3-3H8a3 3 0 0 0-3 3v13");
}

.tpz5dabmt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 20v-4c0-1.317.335-2.748 1.293-3.707l2-2a3.83 3.83 0 0 1 5.414 0l2 2C19.665 13.252 20 14.683 20 16v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

</style>
