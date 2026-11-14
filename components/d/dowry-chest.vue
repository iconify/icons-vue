<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_gx051fv"/><path class="vfijlmb0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dowry-chest" /></template>
<style>
.c_gx051fv {
  d: path("M3 20V8.5a9 4 0 0 1 18 0V20Zm0-10h7m4 0h7M6.5 10v10m11-10v10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfijlmb0h {
  d: path("M11.75 8h.5A1.75 1.75 0 0 1 14 9.75v2a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 11.75v-2A1.75 1.75 0 0 1 11.75 8");
}

</style>
