<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_rw-dber"/><rect class="quzj5hbvw"/><rect class="p7i7bi_ov"/><path class="kh2azqb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gantry-crane" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kh2azqb-n {
  d: path("M10.5 15.25v6m3-6v6");
}

.p7i7bi_ov {
  width: 9.5px;
  height: 6px;
  x: 7.25px;
  y: 15.25px;
  rx: 0.75px;
}

.quzj5hbvw {
  width: 7px;
  height: 4px;
  x: 8.5px;
  y: 8.25px;
  rx: 0.75px;
}

.x_rw-dber {
  d: path("M4 21.25V4.75m16 16.5V4.75m-17.25 0h18.5m-9.25 0v3.5");
}

</style>
