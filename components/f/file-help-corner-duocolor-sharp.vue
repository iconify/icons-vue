<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zdt5grb0s"/><path class="l7dpryp5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-corner-duocolor-sharp" /></template>
<style>
.l7dpryp5e {
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zdt5grb0s {
  stroke-opacity: 0.4;
  d: path("M15 16a2 2 0 1 1 2 2m0 3h.01");
}

</style>
