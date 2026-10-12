<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w8p5jmbuz"/><rect class="o5nw3ij5x"/><path class="zjcakfaac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-bucket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5nw3ij5x {
  width: 4.5px;
  height: 4.5px;
  x: 13.5px;
  y: 6.25px;
  rx: 1px;
}

.w8p5jmbuz {
  width: 4.5px;
  height: 4.5px;
  x: 6px;
  y: 6.25px;
  rx: 1px;
}

.zjcakfaac {
  d: path("M5.75 10.75h12.5q1.5 0 1.25 1.48l-1.25 7.54q-.25 1.48-1.75 1.48h-9q-1.5 0-1.75-1.48L4.5 12.23q-.25-1.48 1.25-1.48m-1 3.25h14.5");
}

</style>
