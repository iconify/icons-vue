<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w1zjl4b3s"/><path class="n5v89obeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leotard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n5v89obeg {
  d: path("M8.5 6.5q3.5 4.5 7 0");
}

.w1zjl4b3s {
  d: path("M8.5 2.5v4c0 1.5-3 2.5-3 5v2l5 8h3l5-8v-2c0-2.5-3-3.5-3-5v-4");
}

</style>
