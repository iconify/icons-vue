<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fvs1j-nnj"/><path class="q1x06zbkp"/><path class="avd-bdbsr"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cigarette-off-sharp-two-tone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.avd-bdbsr {
  stroke-opacity: 0.4;
  d: path("M15 3L16 3C17.6569 3 19 4.3431 19 6L19 7.5C20.6569 7.5 22 8.8431 22 10.5L22 13M19 7.5L16.5 7.5");
}

.fvs1j-nnj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 19L19 21C19 21.5523 18.5523 22 18 22L2 22C1.4477 22 1 21.5523 1 21L1 16C1 15.4477 1.4477 15 2 15L15 15L19 19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1x06zbkp {
  d: path("M18 18L18 21L2 21L2 16L16 16M9.4832 5.2386L10.151 4.4942C10.6341 3.9557 11.25 3.5301 11.9609 3.2714L12.9006 2.9294");
}

</style>
