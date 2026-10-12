<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c3zh0kmzf"/><path class="bk82rubqa"/><rect class="y3_sg4dyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-air-balloon" /></template>
<style>
.bk82rubqa {
  d: path("M10 15.75C8.25 13 8 7 12 3m2 12.75C15.75 13 16 7 12 3M9.75 15.75l.5 3m4-3l-.5 3");
}

.c3zh0kmzf {
  d: path("M12 2.75A7.25 7.25 0 0 0 4.75 10c0 2.6 2 4.5 4.5 5.75h5.5c2.5-1.25 4.5-3.15 4.5-5.75A7.25 7.25 0 0 0 12 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3_sg4dyt {
  width: 4.5px;
  height: 2.5px;
  x: 9.75px;
  y: 18.75px;
  rx: 0.75px;
}

</style>
