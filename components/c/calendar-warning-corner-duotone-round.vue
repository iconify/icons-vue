<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c86daxb4l"/><path class="dl_xnmb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-warning-corner-duotone-round" /></template>
<style>
.c86daxb4l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 9a4 4 0 0 0-4 4v8H8a4 4 0 0 1-4-4V9Z");
}

.dl_xnmb-j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16m-3 5v4m0 3h.01");
}

.ft5dv1b6b {
  fill: none;
}

</style>
