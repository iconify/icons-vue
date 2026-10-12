<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wkg5_f5aq"/><path class="rmp9w4b7v"/><circle class="em9cvctqt"/><path class="ux464eb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-declaration" /></template>
<style>
.em9cvctqt {
  cx: 12px;
  cy: 15px;
  r: 3.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmp9w4b7v {
  d: path("M7 6h10M7 9.5h6");
}

.ux464eb-x {
  d: path("M8.75 15h6.5M12 11.75a6.5 6.5 0 0 0 0 6.5");
}

.wkg5_f5aq {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
