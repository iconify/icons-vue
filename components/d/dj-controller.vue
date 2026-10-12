<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l0ojli41q"/><circle class="jhn2ch9ax"/><circle class="ifs-v5bqs"/><path class="l517yxbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dj-controller" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifs-v5bqs {
  cx: 17px;
  cy: 12px;
  r: 2px;
}

.jhn2ch9ax {
  cx: 7px;
  cy: 12px;
  r: 2px;
}

.l0ojli41q {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2.5px;
}

.l517yxbln {
  d: path("M12 9v6");
}

</style>
