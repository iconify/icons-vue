<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="arzno-wyz"/><path class="o_taswthd"/><path class="cwc236bjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-line-duotone" /></template>
<style>
.arzno-wyz {
  d: path("M8.99991 11.9999H14.9999");
}

.cwc236bjm {
  d: path("M15 6H16C19.3137 6 22 8.68629 22 12C22 15.3137 19.3137 18 16 18H15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_taswthd {
  d: path("M9 18H8C4.68629 18 2 15.3137 2 12C2 8.68629 4.68629 6 8 6H9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
