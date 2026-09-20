<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="js6t3bb6m"/><path class="q9dd829qf"/><path class="f0lu7bcgk"/><path class="mzz93ed1z"/><path class="y0y0ccsoe"/><path class="lmdddlr1e"/><path class="p7w3a5bcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:binoculars-duotone-regular" /></template>
<style>
.f0lu7bcgk {
  d: path("M3 8v11h7V8Z");
}

.js6t3bb6m {
  fill: currentColor;
  d: path("M3 8v11h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lmdddlr1e {
  d: path("M4 5h5");
}

.mzz93ed1z {
  d: path("M14 8v11h7V8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7w3a5bcn {
  d: path("M15 5h5");
}

.q9dd829qf {
  fill: currentColor;
  d: path("M14 8v11h7V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

</style>
