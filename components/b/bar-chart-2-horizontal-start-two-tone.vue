<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t2i8h7vmr"/><path class="rhi6q16-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-horizontal-start-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rhi6q16-e {
  d: path("M2 20L8 20");
}

.t2i8h7vmr {
  stroke-opacity: 0.4;
  d: path("M2 4L22 4M2 12L15 12");
}

</style>
