<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a051g9b-u"/><path class="glmzfbo4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:globe-network" /></template>
<style>
.a051g9b-u {
  d: path("M5.75 8.75a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0");
}

.glmzfbo4x {
  d: path("M9.5 8.75a2.5 6.25 0 1 0 5 0a2.5 6.25 0 1 0-5 0m-3.75 0h12.5M12 15v2.5m-2 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7 0h7m4 0h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
