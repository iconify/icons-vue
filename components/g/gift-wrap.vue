<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qulhj0b6x"/><path class="xkscgdc5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-wrap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qulhj0b6x {
  width: 18px;
  height: 3.5px;
  x: 3px;
  y: 7px;
  rx: 1px;
}

.xkscgdc5m {
  d: path("M4.75 10.5v8.75a2 2 0 0 0 2 2h10.5a2 2 0 0 0 2-2V10.5M12 7v14.25M12 7c-1.5-4-5.75-4.5-5.5-1.75C6.6 6.3 7.4 6.8 8 7m4 0c1.5-4 5.75-4.5 5.5-1.75C17.4 6.3 16.6 6.8 16 7");
}

</style>
