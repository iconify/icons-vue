<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dwqttzvnq"/><path class="ghx06kblg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:doorbuster" /></template>
<style>
.dwqttzvnq {
  d: path("M4 21.5v-19h14v11.6");
}

.ghx06kblg {
  d: path("m6.005 3.216l4 1.428A1.5 1.5 0 0 1 11 6.057v11.886a1.5 1.5 0 0 1-.995 1.413l-4 1.428A1.5 1.5 0 0 1 4 19.371V4.629a1.5 1.5 0 0 1 2.005-1.413M9.25 12h.01m5.49 9.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
