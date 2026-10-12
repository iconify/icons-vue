<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qc13l57zm"/><path class="c44jkob5o"/><rect class="gtjtylbtz"/><path class="zua5yibhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coffee-table" /></template>
<style>
.c44jkob5o {
  d: path("M14.25 7.25H15a1.5 1.5 0 0 1 0 3h-.75");
}

.gtjtylbtz {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 11.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qc13l57zm {
  width: 5px;
  height: 5.5px;
  x: 9.25px;
  y: 5.75px;
  rx: 1px;
}

.zua5yibhg {
  d: path("M5.5 14.25v6.5m13-6.5v6.5M5.5 18h13");
}

</style>
