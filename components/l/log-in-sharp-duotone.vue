<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z9glpybvs"/><path class="q8kx11bqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:log-in-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q8kx11bqf {
  d: path("M13.6493 12L2 12M7.7469 6.204L13.8907 12L7.7469 17.796");
}

.z9glpybvs {
  stroke-opacity: 0.4;
  d: path("M14 4L21 4L21 20L14 20");
}

</style>
