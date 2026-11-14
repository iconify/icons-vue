<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqafw_15k"/><path class="irfpucbfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cabin-fire" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irfpucbfd {
  d: path("M9.75 16a2.5 2.5 0 0 1-2.5-2.5c0-1 .5-1.75 1-2.25c.25.75.5 1.25 1 1.25c0-1.5.25-3 1.25-4.5c0 2 1.75 3.25 1.75 5.5a2.5 2.5 0 0 1-2.5 2.5M18 14.75v3.5M18 21h.01");
}

.kqafw_15k {
  d: path("M9.75 3zA5.25 5.25 0 0 1 15 8.25v7a5.25 5.25 0 0 1-5.25 5.25a5.25 5.25 0 0 1-5.25-5.25v-7A5.25 5.25 0 0 1 9.75 3");
}

</style>
