<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ywosoee9q"/><rect class="co2cc5uei"/><path class="ubpdmogjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:align-bottom" /></template>
<style>
.co2cc5uei {
  width: 5px;
  height: 8.25px;
  x: 13.75px;
  y: 8.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ubpdmogjl {
  d: path("M2.75 20.25h18.5");
}

.ywosoee9q {
  width: 5px;
  height: 13px;
  x: 5.25px;
  y: 3.75px;
  rx: 1.5px;
}

</style>
