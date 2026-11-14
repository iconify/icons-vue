<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zoh9_jbnt"/><path class="fyns9gbrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-safety-check" /></template>
<style>
.fyns9gbrw {
  d: path("M9 5.5h1a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 10 8H9a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 9 5.5m.5 0v-2m-3 0H13m-1.75 3.25h4.25c1.75 0 2.5 1.25 2.5 3V13m-3.25 5l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zoh9_jbnt {
  d: path("M12.673 19.935q-.139.182-.299.347t-.336.31q-.178.146-.37.27q-.193.124-.399.225t-.421.179t-.44.13q-.223.052-.451.078T9.5 21.5q-.197 0-.392-.019q-.196-.02-.388-.058q-.193-.038-.381-.095t-.37-.132t-.355-.168t-.336-.202t-.316-.234q-.151-.125-.29-.264t-.264-.29q-.125-.152-.234-.316q-.109-.163-.202-.336q-.092-.174-.168-.355q-.075-.182-.132-.37t-.095-.381t-.058-.388T5.5 17.5V12q0-.197.019-.392q.02-.196.058-.388q.038-.193.095-.381t.132-.37t.168-.355t.202-.336t.234-.316q.125-.151.264-.29t.29-.264t.316-.234q.163-.109.336-.202q.174-.092.355-.168q.182-.075.37-.132t.381-.095t.388-.058T9.5 8t.392.019q.196.02.388.058q.193.038.381.095t.37.132q.181.076.355.168q.173.093.336.202t.316.234q.151.125.29.264t.264.29t.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388t.019.392v3.477");
}

</style>
