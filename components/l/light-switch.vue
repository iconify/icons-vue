<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="upddb4dxn"/><rect class="q986jvb1v"/><path class="at7ws5bbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-switch" /></template>
<style>
.at7ws5bbl {
  d: path("M9.5 12h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q986jvb1v {
  width: 5px;
  height: 10.5px;
  x: 9.5px;
  y: 6.75px;
  rx: 1.5px;
}

.upddb4dxn {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
