<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ksiibsbdf"/><path class="ue0nez8sv"/><rect class="ea2ec-tvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-day" /></template>
<style>
.ea2ec-tvv {
  width: 5.5px;
  height: 5px;
  x: 9.25px;
  y: 12.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksiibsbdf {
  width: 16.5px;
  height: 15px;
  x: 3.75px;
  y: 5.25px;
  rx: 2.5px;
}

.ue0nez8sv {
  d: path("M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

</style>
