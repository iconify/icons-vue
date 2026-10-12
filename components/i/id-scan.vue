<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u4_9fcb4o"/><path class="q7h42p7rq"/><circle class="hk4_ptb-x"/><path class="h16qlybxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:id-scan" /></template>
<style>
.h16qlybxm {
  d: path("M15.75 17.5L17 18.75l2.25-2.5");
}

.hk4_ptb-x {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7h42p7rq {
  d: path("M10 8.5a2 2 0 1 1-4 0a2 2 0 1 1 4 0M5.5 14c.5-1.4 1.4-2 2.5-2s2 .6 2.5 2M13 8h4.5");
}

.u4_9fcb4o {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
