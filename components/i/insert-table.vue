<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="trd540byi"/><path class="mf7y1czjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insert-table" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mf7y1czjs {
  d: path("M2.75 7.25h12m-6 0v7.5m9.5.5v6m-3-3h6");
}

.trd540byi {
  width: 12px;
  height: 12px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
