<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fonq_mbvk"/><path class="g9r55mb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-vertical-fill" /></template>
<style>
.fonq_mbvk {
  fill: currentColor;
  d: path("M5 6L19 6C20.65685 6 22 7.34315 22 9L22 15C22 16.65685 20.65685 18 19 18L5 18C3.34315 18 2 16.65685 2 15L2 9C2 7.34315 3.34315 6 5 6Z");
  stroke: none;
}

.g9r55mb4m {
  d: path("M3 3H21M3 21H21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
