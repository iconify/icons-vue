<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jsnozbuqk"/><path class="cy7jpy12m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-breed-tabby" /></template>
<style>
.cy7jpy12m {
  d: path("m9.75 11l1-1.75l1.25 1.5l1.25-1.5l1 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsnozbuqk {
  d: path("m5 11l.75-7.5L10 7q2-.5 4 0l4.25-3.5L19 11c0 5.75-3.25 9.5-7 9.5S5 16.75 5 11m.5 3.75l3 1m10-1l-3 1M9.25 13.5h.01m5.49 0h.01");
}

</style>
