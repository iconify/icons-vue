<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z43nfgbva"/><path class="e030h51ix"/><path class="pn-mm5bcv"/><path class="ymw3aibdo"/><path class="tla8vyn6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cherry-pick-outline-thin" /></template>
<style>
.e030h51ix {
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pn-mm5bcv {
  d: path("M17 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tla8vyn6c {
  d: path("M12 7v8");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z43nfgbva {
  d: path("M3 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
