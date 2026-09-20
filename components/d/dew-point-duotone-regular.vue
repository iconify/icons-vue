<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-6v8o44a"/><path class="j9mpubb9t"/><path class="l0q87g1mm"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dew-point-duotone-regular" /></template>
<style>
.j9mpubb9t {
  d: path("m12 6 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.l0q87g1mm {
  d: path("M20 14a8 8 0 0 1 -16 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-6v8o44a {
  fill: currentColor;
  d: path("m12 6 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

</style>
