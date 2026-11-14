<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xz3rcacmm"/><path class="oeut2vble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:creatine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oeut2vble {
  d: path("M9.75 13h4.5A1.75 1.75 0 0 1 16 14.75v1.5A1.75 1.75 0 0 1 14.25 18h-4.5A1.75 1.75 0 0 1 8 16.25v-1.5A1.75 1.75 0 0 1 9.75 13M5.5 4a3 3 0 0 0 6 0Zm6 0L18 2.5");
}

.xz3rcacmm {
  d: path("M4.5 10v8.5A2.5 2.5 0 0 0 7 21h10a2.5 2.5 0 0 0 2.5-2.5V10M5 7h14a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 19 10H5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 5 7");
}

</style>
