<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pphsu-i_k"/><path class="y2aenm0zw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-wrap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pphsu-i_k {
  d: path("M6 7h12.5a2.5 5 0 0 1 0 10H6");
}

.y2aenm0zw {
  d: path("M3 12a3 5 0 1 0 6 0a3 5 0 1 0-6 0m9.5-5v10m3-10v10M6 12h.01");
}

</style>
