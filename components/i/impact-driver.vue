<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trxcbqdca"/><rect class="pu43aeu0w"/><path class="i45nkg65n"/><rect class="ghz0vx8ov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:impact-driver" /></template>
<style>
.ghz0vx8ov {
  width: 9px;
  height: 4.5px;
  x: 5px;
  y: 15.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i45nkg65n {
  d: path("M16.5 7.75h2.25");
}

.pu43aeu0w {
  width: 4px;
  height: 4px;
  x: 12.5px;
  y: 5.75px;
  rx: 0.75px;
}

.trxcbqdca {
  d: path("M8.5 5h3a1 1 0 0 1 1 1v3.5a1 1 0 0 1-1 1H11l.5 5.25H7.25l.5-5.25h.75a2.75 2.75 0 0 1 0-5.5");
}

</style>
