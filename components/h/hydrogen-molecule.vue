<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t48pgf-bj"/><path class="tqd-eiexg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hydrogen-molecule" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t48pgf-bj {
  d: path("M2.5 16.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m9.5-9.5a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m-1.25 6l2.5-2.5");
}

.tqd-eiexg {
  d: path("M4.75 16.75a2.5 2.5 0 0 1 2.5-2.5m7-7a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
