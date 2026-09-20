<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e8jhv79aa"/><path class="f1oz8g1ru"/><path class="tpkkoibhl"/><path class="mu5pjkbqo"/><path class="rnv77s7xr"/><path class="it0a8bbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chess-duotone-regular" /></template>
<style>
.e8jhv79aa {
  fill: currentColor;
  d: path("M3 3v18h18V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f1oz8g1ru {
  fill: currentColor;
  d: path("M7 7h3v3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.it0a8bbrp {
  d: path("M14 14h3v3h-3Z");
}

.mu5pjkbqo {
  d: path("M3 3v18h18V3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rnv77s7xr {
  d: path("M7 7h3v3H7Z");
}

.tpkkoibhl {
  fill: currentColor;
  d: path("M14 14h3v3h-3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
