<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wf8rrh0yx"/><rect class="syfhfzvtt"/><path class="rmkxbz6eq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmkxbz6eq {
  d: path("M6.5 9.5q5.5-4.75 11 0M6.5 18h11M9 7.85v13.4m3-14.1v14.1m3-13.4v13.4");
}

.syfhfzvtt {
  width: 3px;
  height: 16.75px;
  x: 18.25px;
  y: 4.5px;
  rx: 0.75px;
}

.wf8rrh0yx {
  width: 3px;
  height: 16.75px;
  x: 2.75px;
  y: 4.5px;
  rx: 0.75px;
}

</style>
