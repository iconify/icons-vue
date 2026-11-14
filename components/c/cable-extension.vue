<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bi1xf-bwn"/><path class="ibc784bni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-extension" /></template>
<style>
.bi1xf-bwn {
  d: path("M5 2.5v2m3-2v2m-4.5 0h6V7a3 3 0 0 1-6 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibc784bni {
  d: path("M6.5 10v4a3 3 0 0 0 3 3H12m3.5-4H18a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 18 21h-2.5a3.5 3.5 0 0 1-3.5-3.5v-1a3.5 3.5 0 0 1 3.5-3.5m-.5 4h.01m3.49 0h.01");
}

</style>
