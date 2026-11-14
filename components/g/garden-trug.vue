<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eo7spyy2f"/><path class="ccp7upbrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-trug" /></template>
<style>
.ccp7upbrb {
  d: path("M7 12V7.5a5 5 0 0 1 10 0V12M4 15.75h16");
}

.eo7spyy2f {
  d: path("M5.085 12h13.83a1.75 1.75 0 0 1 1.625 2.4l-1.6 4a1.75 1.75 0 0 1-1.625 1.1H6.685a1.75 1.75 0 0 1-1.625-1.1l-1.6-4A1.75 1.75 0 0 1 5.085 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
