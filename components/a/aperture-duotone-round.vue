<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c3-9r1bmd"/><path class="aywpskbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aperture-duotone-round" /></template>
<style>
.aywpskbmc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m0 0l10-5M9 4l8 6m0-5v9m4-2l-10 5m4 3l-8-6m0 5v-9");
}

.c3-9r1bmd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 12a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9m10-5l-.008.004l-.003.001l-5.978 2.989l-.004.003L7 10v4l.008.006l3.982 2.987l.003.002L11 17l.008-.004l.003-.001l5.978-2.989l.004-.003L17 14v-4l-3.99-2.993l-.004-.002Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
