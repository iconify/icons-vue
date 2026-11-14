<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vay_nl08k"/><path class="f36nipz_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-meter-box" /></template>
<style>
.f36nipz_v {
  d: path("M8.75 12.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m3.25 0l1.5-1.5M12 18.5v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vay_nl08k {
  d: path("M7.375 2.5h9.25A4.375 4.375 0 0 1 21 6.875v7.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 14.125v-7.25A4.375 4.375 0 0 1 7.375 2.5M3 6.5h18");
}

</style>
