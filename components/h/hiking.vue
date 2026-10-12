<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xa-sitzqx"/><path class="y2p0c2arf"/><rect class="a47dzkudq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hiking" /></template>
<style>
.a47dzkudq {
  width: 3.5px;
  height: 5.5px;
  x: 4.75px;
  y: 8.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xa-sitzqx {
  cx: 13.25px;
  cy: 4.75px;
  r: 2px;
}

.y2p0c2arf {
  d: path("M12.25 8.75L10.5 14l2.75 3l-.5 4.25M10.5 14l-2 3.5L7 21.25m5.25-11.5l2.25 2.5L17 12m.75-2.25v11.5");
}

</style>
