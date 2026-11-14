<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f84doxbug"/><path class="rvlg7-cpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-match" /></template>
<style>
.f84doxbug {
  d: path("M3 9.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rvlg7-cpb {
  d: path("M9 9.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m5.75 8.5l2 2L21 15.75");
}

</style>
