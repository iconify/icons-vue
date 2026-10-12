<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ysic-s1le"/><circle class="luhopnlkq"/><circle class="szlzq8b5o"/><circle class="szl4zybhx"/><path class="em-zk6b8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gymnastic-rings" /></template>
<style>
.em-zk6b8y {
  d: path("M7 9.5h10m-5 0v6.25l-1 5.5m1-5.5l1 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.luhopnlkq {
  cx: 5.25px;
  cy: 9.5px;
  r: 1.75px;
}

.szl4zybhx {
  cx: 12px;
  cy: 5.75px;
  r: 1.75px;
}

.szlzq8b5o {
  cx: 18.75px;
  cy: 9.5px;
  r: 1.75px;
}

.ysic-s1le {
  d: path("M5.25 2.75v5m13.5-5v5");
}

</style>
