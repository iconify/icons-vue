<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xuznnacny"/><path class="qrp1owrzw"/><path class="nrzizubal"/><path class="uu-axlbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:engagement-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrzizubal {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.qrp1owrzw {
  fill: currentColor;
  d: path("m9 8 3 -3 3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uu-axlbah {
  d: path("m9 8 3 -3 3 3Z");
}

.xuznnacny {
  fill: currentColor;
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
