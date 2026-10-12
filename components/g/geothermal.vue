<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oz683kbwp"/><circle class="ts6ik8buj"/><path class="ymd_5iu5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:geothermal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oz683kbwp {
  width: 18.5px;
  height: 8.75px;
  x: 2.75px;
  y: 12.5px;
  rx: 2.5px;
}

.ts6ik8buj {
  cx: 12px;
  cy: 16.875px;
  r: 2px;
}

.ymd_5iu5a {
  d: path("M8 9.5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5");
}

</style>
