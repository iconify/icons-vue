<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uc8t9cclk"/><rect class="vepwvyb3p"/><path class="xaxkeobxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunar-module" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uc8t9cclk {
  d: path("M9.5 3.5h5q1 0 1.47.88l.81 1.49q.47.88 0 1.76l-.81 1.49q-.47.88-1.47.88h-5q-1 0-1.47-.88l-.81-1.49q-.47-.88 0-1.76l.81-1.49Q8.5 3.5 9.5 3.5m.75 3.25h3.5");
}

.vepwvyb3p {
  width: 11px;
  height: 4px;
  x: 6.5px;
  y: 12.25px;
  rx: 1px;
}

.xaxkeobxq {
  d: path("m7.75 16.25l-3.25 5m11.75-5l3.25 5m-16.75 0h3.5m11.5 0h3.5");
}

</style>
