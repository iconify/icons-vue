<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxapzkbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:actuator" /></template>
<style>
.xxapzkbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7h1.5A1.75 1.75 0 0 1 7.5 8.75v6.5A1.75 1.75 0 0 1 5.75 17h-1.5a1.75 1.75 0 0 1-1.75-1.75v-6.5A1.75 1.75 0 0 1 4.25 7m5 2h5.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 14.75 15h-5.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 9.25 9m7.25 3h5m0-2.5v5");
}

</style>
