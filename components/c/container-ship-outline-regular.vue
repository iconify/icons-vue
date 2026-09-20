<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r1dvx0b7e"/><path class="v7vovvuwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:container-ship-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1dvx0b7e {
  d: path("m2 14 4 4h12l4 -4");
}

.v7vovvuwg {
  d: path("M7 9.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2V12a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
