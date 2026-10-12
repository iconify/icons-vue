<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lz2v-bc6z"/><path class="n7pnhbcpt"/><circle class="lt_te9bsy"/><path class="yfto44_fd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:driver-log" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lt_te9bsy {
  cx: 13.75px;
  cy: 12px;
  r: 3.75px;
}

.lz2v-bc6z {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 1.5px;
}

.n7pnhbcpt {
  d: path("M7.5 2.75v18.5");
}

.yfto44_fd {
  d: path("M10 12h2.25m3 0h2.25m-3.75 1.5v2.25m0-3.75h.01");
}

</style>
