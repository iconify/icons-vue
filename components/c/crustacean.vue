<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i4qlvp0mp"/><path class="jo8l0n71h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crustacean" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4qlvp0mp {
  d: path("M6 14a6 4 0 1 0 12 0a6 4 0 1 0-12 0m3-3.5l-2-3C4.5 7 4 4.5 5.5 3M7 7.5C9.5 7 9.75 4.5 8.75 3");
}

.jo8l0n71h {
  d: path("m15 10.5l2-3c2.5-.5 3-3 1.5-4.5M17 7.5c-2.5-.5-2.75-3-1.75-4.5M6.5 12L3 10.5M6 14H2.5m4 2L3 17.5m5 0l-3 3M17.5 12l3.5-1.5M18 14h3.5m-4 2l3.5 1.5m-5 0l3 3");
}

</style>
