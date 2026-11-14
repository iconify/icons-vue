<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5d0nsbbk"/><path class="g15c_k0_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-pool" /></template>
<style>
.c5d0nsbbk {
  d: path("M5.75 19H4.5a1 1 0 0 1-1-1v-2.5A1.5 1.5 0 0 1 5 14h1.25L8 11.25a1.5 1.5 0 0 1 1.25-.75h4.5a1.5 1.5 0 0 1 1.25.75L16.75 14H19a1.5 1.5 0 0 1 1.5 1.5V18a1 1 0 0 1-1 1h-2m-8.25 0H14");
}

.g15c_k0_f {
  d: path("M5.75 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M14 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M6.5 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
