<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zyjjajb-o"/><path class="kvwa3vrkc"/><path class="wn5bpvbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-archive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvwa3vrkc {
  d: path("M4.25 10.5h15.5v7.25a2.5 2.5 0 0 1-2.5 2.5H6.75a2.5 2.5 0 0 1-2.5-2.5Z");
}

.wn5bpvbod {
  d: path("M9.75 13h4.5a.75.75 0 0 1 .75.75v3a.75.75 0 0 1-.75.75h-4.5a.75.75 0 0 1-.75-.75v-3a.75.75 0 0 1 .75-.75m-.5.5L12 15.25l2.75-1.75");
}

.zyjjajb-o {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 1.25px;
}

</style>
