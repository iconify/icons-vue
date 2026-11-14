<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrg_5qb8d"/><path class="ru435juci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:commission-tier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrg_5qb8d {
  d: path("M2.5 20.5h19v-11h-6v4H9V17H2.5Z");
}

.ru435juci {
  d: path("M15 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
