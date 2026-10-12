<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ksiibsbdf"/><path class="zyxne-bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-event" /></template>
<style>
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

.zyxne-bmk {
  d: path("M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5m-5 5.25h2q.5 0 .5.5v4.25q0 .5-.38.18l-.74-.61q-.38-.32-.76 0l-.74.61q-.38.32-.38-.18V13q0-.5.5-.5");
}

</style>
