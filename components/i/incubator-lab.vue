<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wlbon9pvw"/><path class="oq5i6491y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incubator-lab" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oq5i6491y {
  d: path("M7.75 11.5h5.5A1.75 1.75 0 0 1 15 13.25v3A1.75 1.75 0 0 1 13.25 18h-5.5A1.75 1.75 0 0 1 6 16.25v-3a1.75 1.75 0 0 1 1.75-1.75M6 14.75h9m3 0h.01m-8.01-9c-1-1 1-2.25 0-3.25m4 3.25c-1-1 1-2.25 0-3.25");
}

.wlbon9pvw {
  d: path("M6.5 8.5h11A3.5 3.5 0 0 1 21 12v5.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5V12a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
