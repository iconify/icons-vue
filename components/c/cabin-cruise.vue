<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="s7etx_b3c"/><path class="l5zl5sb0i"/><rect class="boxs_9b5h"/><rect class="l56tsha6x"/><path class="x_nou4b8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cabin-cruise" /></template>
<style>
.boxs_9b5h {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 14.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l56tsha6x {
  width: 4.5px;
  height: 3.25px;
  x: 5px;
  y: 11px;
  rx: 1.25px;
}

.l5zl5sb0i {
  d: path("M13 7.75c.8-.6 1.7-.6 2.5 0s1.7.6 2.5 0M2.75 9.5v4.75");
}

.s7etx_b3c {
  cx: 15.5px;
  cy: 7.5px;
  r: 3.75px;
}

.x_nou4b8l {
  d: path("M4.75 18.25v3m14.5-3v3");
}

</style>
