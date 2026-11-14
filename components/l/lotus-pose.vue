<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkxiz5b3c"/><path class="ya-sgg1ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lotus-pose" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkxiz5b3c {
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M5.75 16.5l2.75-6h7l2.75 6m-6.25-6v5");
}

.ya-sgg1ye {
  d: path("M3 18.5c3-4 15-4 18 0c-3 3.5-15 3.5-18 0");
}

</style>
