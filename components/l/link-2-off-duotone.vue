<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pa7_6bc8x"/><path class="ayo73pbzj"/><path class="n_31o8b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link-2-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.n_31o8b2c {
  stroke-opacity: 0.4;
  d: path("M15 7L17 7C19.7614 7 22 9.2386 22 12C22 13.2135 21.5677 14.326 20.8488 15.1919");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pa7_6bc8x {
  stroke-opacity: 0.4;
  d: path("M9 17L7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7M17 17L15 17M8 12L12 12");
}

</style>
