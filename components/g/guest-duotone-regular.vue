<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tmy26410t"/><path class="mil5mpb-p"/><path class="p6pqx6b7w"/><path class="rrxso7m3p"/><path class="i49-5fazd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guest-duotone-regular" /></template>
<style>
.i49-5fazd {
  d: path("M13 17a4 4 0 0 1 8 0");
}

.mil5mpb-p {
  fill: currentColor;
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6pqx6b7w {
  d: path("M2 3v18h8V3Z");
}

.rrxso7m3p {
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.tmy26410t {
  fill: currentColor;
  d: path("M2 3v18h8V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
