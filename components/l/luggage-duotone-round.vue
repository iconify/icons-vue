<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i83_glbni"/><path class="ualionbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i83_glbni {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 7h6a4 4 0 0 1 4 4v6a2 2 0 0 1-2 2a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732h-2a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4");
}

.ualionbsq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v6a2 2 0 0 1-2 2m-6 0h2m-6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3");
}

</style>
