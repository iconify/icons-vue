<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cmgfcn8sj"/><path class="fqms87g1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-sharp-duotone" /></template>
<style>
.cmgfcn8sj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 11L22 22C22 22.55 21.55 23 21 23L3 23C2.45 23 2 22.55 2 22L2 11C2 10.69 2.14 10.4 2.39 10.21L11.39 3.21C11.75 2.93 12.25 2.93 12.61 3.21L14 4.2856L14 11L22 11Z");
  stroke: none;
}

.fqms87g1z {
  d: path("M9 23L9 15L15 15L15 23M20.2929 1.7071L17 5L21 5L17.7071 8.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
