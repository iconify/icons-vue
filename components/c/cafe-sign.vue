<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybc8bibse"/><path class="qwu0bsbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cafe-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qwu0bsbls {
  d: path("M8 12.5h7v2a3.5 3.5 0 0 1-7 0Zm7 1a1.75 1.75 0 0 1 0 3.5");
}

.ybc8bibse {
  d: path("M3 4h17.5m-13 0v3.5m9-3.5v3.5M7 7.5h10a3.5 3.5 0 0 1 3.5 3.5v6a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 17v-6A3.5 3.5 0 0 1 7 7.5");
}

</style>
