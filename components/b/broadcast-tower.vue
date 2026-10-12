<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m-j6pf-uw"/><path class="q_jb7mhbr"/><path class="rmt6ffdly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:broadcast-tower" /></template>
<style>
.m-j6pf-uw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.25L12 10l4 11.25m-6.4-4.5h4.8");
}

.q_jb7mhbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.5h.01");
}

.rmt6ffdly {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.17 3.67a4 4 0 0 0 0 5.66m5.66-5.66a4 4 0 0 1 0 5.66");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
