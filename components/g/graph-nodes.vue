<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dgk39q_4m"/><circle class="tc9ytgh7v"/><circle class="ojoszltjo"/><circle class="wayizpwxs"/><path class="e9kp5342n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graph-nodes" /></template>
<style>
.dgk39q_4m {
  cx: 5.5px;
  cy: 5.5px;
  r: 2.25px;
}

.e9kp5342n {
  d: path("m8.96 6.03l6.08.94M5.5 9v4.5m12.37-2.56l-.74 4.12m-8.16 2.41l4.06.56M7.76 8.17l6.48 7.66");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojoszltjo {
  cx: 5.5px;
  cy: 17px;
  r: 2.25px;
}

.tc9ytgh7v {
  cx: 18.5px;
  cy: 7.5px;
  r: 2.25px;
}

.wayizpwxs {
  cx: 16.5px;
  cy: 18.5px;
  r: 2.25px;
}

</style>
