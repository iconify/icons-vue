<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wgt7cdc-z"/><path class="m6yg03b1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bed-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m6yg03b1v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5v14M3 9h14a4 4 0 0 1 4 4v6M3 16h18M7 9v7");
}

.wgt7cdc-z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 8h14a5 5 0 0 1 5 5v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
