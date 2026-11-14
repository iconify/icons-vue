<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h22e_ykqe"/><path class="zzqsrdify"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-arrow-merge-right" /></template>
<style>
.h22e_ykqe {
  d: path("M6.5 20.5v-4c0-4 8-4 8-8v-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzqsrdify {
  d: path("m11 7l3.5-3.5L18 7");
}

</style>
