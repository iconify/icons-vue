<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o6n0rrbmd"/><path class="pni1bpm0u"/><path class="wxfc8bn6j"/><path class="oa7ibkb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:liveness-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o6n0rrbmd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oa7ibkb8p {
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
}

.pni1bpm0u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.32 10a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wxfc8bn6j {
  d: path("M5 6h3l2 -2 4 4 2 -2h3");
}

</style>
