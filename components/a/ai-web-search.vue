<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg9c45b1k"/><path class="a-efvwbtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-web-search" /></template>
<style>
.a-efvwbtu {
  d: path("M7.5 10.5a3 7 0 1 0 6 0a3 7 0 1 0-6 0m-4 0h14m-2 5l5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg9c45b1k {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
