<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mrs0pqb1o"/><path class="i7l0ccctm"/><circle class="ywzhblbsk"/><path class="g1ok-obns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-clock-sharp" /></template>
<style>
.g1ok-obns {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 15v2l1.25.75");
}

.i7l0ccctm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M8 17h.01");
}

.mrs0pqb1o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 20.25h-7v-15h16.5v5.5M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywzhblbsk {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
