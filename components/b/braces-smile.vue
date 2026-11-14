<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oep7ahb2o"/><path class="lx83bp9ev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:braces-smile" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lx83bp9ev {
  d: path("M6.25 10.25zA.75.75 0 0 1 7 11a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75a.75.75 0 0 1 .75-.75m3.75 0za.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75a.75.75 0 0 1 .75-.75m4 0za.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75a.75.75 0 0 1 .75-.75m3.75 0za.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75A.75.75 0 0 1 17 11a.75.75 0 0 1 .75-.75");
}

.oep7ahb2o {
  d: path("M2.5 7h19c0 6.5-4 10.5-9.5 10.5S2.5 13.5 2.5 7m2 4h15");
}

</style>
