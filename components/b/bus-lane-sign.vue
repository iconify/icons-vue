<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d1mn339oe"/><path class="aytbzxbuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-lane-sign" /></template>
<style>
.aytbzxbuj {
  d: path("M7.5 13V7A1.5 1.5 0 0 1 9 5.5h6A1.5 1.5 0 0 1 16.5 7v6Zm0-3.5h9m-7 3.5v1.75m5-1.75v1.75");
}

.d1mn339oe {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v8a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 14V6A3.5 3.5 0 0 1 7 2.5m5 15v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
