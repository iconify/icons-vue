<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mc5s_la1h"/><path class="drlhfzbvx"/><circle class="jo45v1frk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:live-caption-bubble" /></template>
<style>
.drlhfzbvx {
  d: path("M6.25 10.25h8.5m-8.5 3.5h4m2 0h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo45v1frk {
  cx: 19px;
  cy: 5px;
  r: 2.25px;
}

.mc5s_la1h {
  width: 15.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2.5px;
}

</style>
