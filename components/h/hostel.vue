<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdwk7wbqv"/><rect class="v5gdxollj"/><rect class="tgn2bdbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hostel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tgn2bdbov {
  width: 4.5px;
  height: 2.5px;
  x: 7.25px;
  y: 13px;
  rx: 1.25px;
}

.v5gdxollj {
  width: 4.5px;
  height: 2.5px;
  x: 7.25px;
  y: 5.5px;
  rx: 1.25px;
}

.xdwk7wbqv {
  d: path("M4.25 3.25v18m15.5-18v18M4.25 10.5h15.5M4.25 18h15.5m-3-7.5V18m0-3.75h3");
}

</style>
