<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqgzs9b2w"/><path class="rma_kdbra"/><path class="bi_con2tg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-test" /></template>
<style>
.bi_con2tg {
  d: path("M14 8.25h2.5m-8.5 6h8.5M8 17.75h5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rma_kdbra {
  fill: currentColor;
  d: path("M9.25 5.25C10.75 7 11.5 8 11.5 9c0 1.25-1 2.25-2.25 2.25S7 10.25 7 9c0-1 .75-2 2.25-3.75");
}

.sqgzs9b2w {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5");
}

</style>
