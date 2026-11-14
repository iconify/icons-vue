<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etwfw681o"/><path class="e5iy09buu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fishing-boat" /></template>
<style>
.e5iy09buu {
  d: path("M14.75 8.5h2a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 16.75 14h-2A1.75 1.75 0 0 1 13 12.25v-2a1.75 1.75 0 0 1 1.75-1.75M8 14V3.5m0 1L3.5 11m11 0H17");
}

.etwfw681o {
  d: path("M5.43 14h13.14a1.75 1.75 0 0 1 1.541 2.58l-1.615 3a1.75 1.75 0 0 1-1.541.92h-9.91a1.75 1.75 0 0 1-1.541-.92l-1.615-3A1.75 1.75 0 0 1 5.43 14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
