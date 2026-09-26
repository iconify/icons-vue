<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oh14ly7za"/><path class="rk0--obfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-vertical-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oh14ly7za {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6L19 6C20.65685 6 22 7.34315 22 9L22 15C22 16.65685 20.65685 18 19 18L5 18C3.34315 18 2 16.65685 2 15L2 9C2 7.34315 3.34315 6 5 6Z");
  stroke: none;
}

.rk0--obfd {
  d: path("M5 7L19 7C20.10457 7 21 7.89543 21 9L21 15C21 16.10457 20.10457 17 19 17L5 17C3.89543 17 3 16.10457 3 15L3 9C3 7.89543 3.89543 7 5 7ZM3 3H21M3 21H21");
}

</style>
