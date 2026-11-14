<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yipd81wwp"/><path class="w7dewy44y"/><path class="jfybk2bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cycling-tour" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfybk2bcg {
  d: path("M15.75 3.5H13.5l3.75 7.5M18 21.75c-2-2-3-3.5-3-4.75a3 3 0 0 1 6 0c0 1.25-1 2.75-3 4.75M18 17h.01");
}

.w7dewy44y {
  d: path("m6.5 11l3-5.5h5L12 11Z");
}

.yipd81wwp {
  d: path("M2.5 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0m18.596 1.099q.154-.539.154-1.099q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37t-.168-.355t-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264q-.152-.125-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T17.25 7t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388t-.019.392q0 .53.138 1.041q.138.512.404.97");
}

</style>
