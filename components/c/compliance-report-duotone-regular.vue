<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h7b39acqd"/><path class="t9j47gpqn"/><path class="rre72cecl"/><path class="ij88zsb1s"/><path class="rqkgxvbhn"/><path class="yn4h-38_p"/><path class="x4y_d5b4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compliance-report-duotone-regular" /></template>
<style>
.h7b39acqd {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ij88zsb1s {
  d: path("M5 6h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqkgxvbhn {
  d: path("M5 10h5");
}

.rre72cecl {
  d: path("M2 4a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.t9j47gpqn {
  fill: currentColor;
  d: path("M16 9h6v4l-3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x4y_d5b4a {
  d: path("M16 9h6v4l-3 3 -3 -3Z");
}

.yn4h-38_p {
  d: path("M5 14h3");
}

</style>
