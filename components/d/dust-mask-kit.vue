<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hc3v33pjv"/><path class="cm-h74b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dust-mask-kit" /></template>
<style>
.cm-h74b3x {
  d: path("M4 6.25c-2 0-2 4.5.25 5.25M17 6.25c2.5 0 2.5 4.5-.25 5.25M18 15v6m-3-3h6");
}

.hc3v33pjv {
  d: path("M4 5.25c3-1.5 10-1.5 13 0v4c0 4-3 6.5-6.5 6.5S4 13.25 4 9.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
