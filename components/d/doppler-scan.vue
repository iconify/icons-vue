<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzwc64bwq"/><path class="a28wo5bxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:doppler-scan" /></template>
<style>
.a28wo5bxn {
  d: path("M6.804 7a6 6 0 0 1 10.392 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tzwc64bwq {
  d: path("M2.5 11.5h19m-19 9h19M6 16h11m-2-2l2 2l-2 2M9.402 8.5a3 3 0 0 1 5.196 0");
}

</style>
