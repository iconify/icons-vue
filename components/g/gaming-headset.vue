<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pnxpsmb4r"/><rect class="vpydkac3y"/><rect class="zdb9ckbuz"/><path class="p0l4u3lbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gaming-headset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p0l4u3lbm {
  d: path("M5.25 14.75v3m13.5-3v3m-11 .25c1.5 2 3.5 3 6.25 3");
}

.pnxpsmb4r {
  d: path("M4.5 12v-.75a7.5 7.5 0 0 1 15 0V12");
}

.vpydkac3y {
  width: 5px;
  height: 8px;
  x: 2.75px;
  y: 12px;
  rx: 2px;
}

.zdb9ckbuz {
  width: 5px;
  height: 8px;
  x: 16.25px;
  y: 12px;
  rx: 2px;
}

</style>
