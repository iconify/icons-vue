<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6my1zbvt"/><path class="d_ky6ccvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calcite-crystal" /></template>
<style>
.d_ky6ccvq {
  d: path("M8 8h8l5-3m-5 3l-4 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6my1zbvt {
  d: path("M6.142 19h5.443a1.5 1.5 0 0 0 .771-.214l4.188-2.512a1.5 1.5 0 0 0 .638-.774l3.086-8.487A1.5 1.5 0 0 0 18.858 5h-5.443a1.5 1.5 0 0 0-.771.214L8.456 7.726a1.5 1.5 0 0 0-.638.774l-3.086 8.487A1.5 1.5 0 0 0 6.142 19M2.5 19h19");
}

</style>
