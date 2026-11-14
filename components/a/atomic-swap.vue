<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7enojbyq"/><path class="a2z5xvbpc"/><path class="i2ptecbdr"/><path class="qycj39xxt"/><path class="dj2ytohhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atomic-swap" /></template>
<style>
.a2z5xvbpc {
  d: path("M2.75 5L7 7.5L11.25 5M7 7.5v4.75m10.761-.053l2.75 1.618a1.5 1.5 0 0 1 .739 1.293v3.034a1.5 1.5 0 0 1-.739 1.293l-2.75 1.618a1.5 1.5 0 0 1-1.522 0l-2.75-1.618a1.5 1.5 0 0 1-.739-1.293v-3.034a1.5 1.5 0 0 1 .739-1.293l2.75-1.618a1.5 1.5 0 0 1 1.522 0");
}

.dj2ytohhv {
  d: path("M3.25 16.75L5 15l1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2ptecbdr {
  d: path("m12.75 14.25l4.25 2.5l4.25-2.5M17 16.75v4.75m-2.5-17H17a2 2 0 0 1 2 2V9");
}

.o7enojbyq {
  d: path("m7.761 2.947l2.75 1.618a1.5 1.5 0 0 1 .739 1.293v3.034a1.5 1.5 0 0 1-.739 1.293l-2.75 1.618a1.5 1.5 0 0 1-1.522 0l-2.75-1.618a1.5 1.5 0 0 1-.739-1.293V5.858a1.5 1.5 0 0 1 .739-1.293l2.75-1.618a1.5 1.5 0 0 1 1.522 0");
}

.qycj39xxt {
  d: path("M17.25 7.25L19 9l1.75-1.75M9.5 19.5H7a2 2 0 0 1-2-2V15");
}

</style>
