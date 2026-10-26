<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hrder_yhr"/><path clip-rule="evenodd" class="ndu83prsu"/><path class="m6ftqsblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:construction-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hrder_yhr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 11C23 11.5523 22.5523 12 22 12L2 12C1.4477 12 1 11.5523 1 11L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.m6ftqsblr {
  d: path("M6 11L6 20M18 11L18 20M3 20L9 20M15 20L21 20");
}

.ndu83prsu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.0858 12L12.0858 3L14.9142 3L5.9142 12L3.0858 12ZM9.0858 12L18.0858 3L20.9142 3L11.9142 12L9.0858 12Z");
  stroke: none;
}

</style>
