<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q528orbwt"/><path class="brio4-vja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:climbing-frame" /></template>
<style>
.brio4-vja {
  d: path("M7.5 18a4.5 11.5 0 0 1 9 0M4.25 12.5h15.5M2.5 18h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q528orbwt {
  d: path("M3 18a9 11.5 0 0 1 18 0");
}

</style>
