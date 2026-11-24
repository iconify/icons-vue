<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nppu5sxnl"/><path class="m0oacccls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-plus-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m0oacccls {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h8a4 4 0 0 1 3.464 2M8 9V7a4 4 0 1 1 8 0v2m-1 9h6m-3-3v6");
}

.nppu5sxnl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 21a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h7a4 4 0 0 0-4 4v8Z");
}

</style>
