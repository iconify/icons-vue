<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dpra8nb8c"/><path class="rpvjsebmn"/><path class="dhm9wy0nm"/><path class="wy8f0maog"/><path class="pt0xyi7kd"/><path class="e6q34etyy"/><path class="dahw1rbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-precision-duotone-regular" /></template>
<style>
.dahw1rbat {
  d: path("M18 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dhm9wy0nm {
  d: path("M3 5h10");
}

.dpra8nb8c {
  fill: currentColor;
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e6q34etyy {
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt0xyi7kd {
  d: path("M3 17h10");
}

.rpvjsebmn {
  fill: currentColor;
  d: path("M18 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wy8f0maog {
  d: path("M3 11h10");
}

</style>
