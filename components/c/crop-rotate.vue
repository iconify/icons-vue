<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt1rkhbrg"/><path class="vcz-kcbce"/><path class="c3jyl9b_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crop-rotate" /></template>
<style>
.c3jyl9b_j {
  d: path("m17.5 9l2 2l1.75-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcz-kcbce {
  d: path("M3.5 8.5H15V20M11 2.5a8.5 8.5 0 0 1 8.5 8.5");
}

.yt1rkhbrg {
  d: path("M6.5 5.5V16H18");
}

</style>
