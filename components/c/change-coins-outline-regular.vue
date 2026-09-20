<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lvh9_ibac"/><path class="quhyyobjk"/><path class="gae_-ztyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:change-coins-outline-regular" /></template>
<style>
.gae_-ztyd {
  d: path("M13.5 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.lvh9_ibac {
  d: path("M8.5 7.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.quhyyobjk {
  d: path("M2.5 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
