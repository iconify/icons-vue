<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5op5zbns"/><path class="xbk7t3bpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loop-the-loop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbk7t3bpn {
  d: path("M18.25 15.25L21 18l-2.75 2.75");
}

.z5op5zbns {
  d: path("M3 18c7 0 14-4 14-9.5a5 5 0 0 0-10 0C7 14 14 18 21 18");
}

</style>
