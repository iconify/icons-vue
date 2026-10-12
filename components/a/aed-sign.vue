<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="sb7m5f9qz"/><path class="wbr-aqbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aed-sign" /></template>
<style>
.a_-q_pb0z {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sb7m5f9qz {
  d: path("M12 19s-6.75-3.75-6.75-8.25A3.4 3.4 0 0 1 12 8.85a3.4 3.4 0 0 1 6.75 1.9C18.75 15.25 12 19 12 19");
}

.wbr-aqbwt {
  d: path("m12.75 11.25l-2 2.75h2.5l-2 2.75");
}

</style>
