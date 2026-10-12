<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ucxu3gbut"/><circle class="mcpohmiso"/><path class="yw_-ek1oe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:id-card-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcpohmiso {
  cx: 8.5px;
  cy: 10.5px;
  r: 2px;
}

.ucxu3gbut {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

.yw_-ek1oe {
  d: path("M5.75 16c.5-1.3 1.6-2 2.75-2s2.25.7 2.75 2M14 10h3.75M14 13.5h2.5");
}

</style>
