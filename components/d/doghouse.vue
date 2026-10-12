<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ppnauzbbl"/><path class="ccxivbcno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:doghouse" /></template>
<style>
.ccxivbcno {
  d: path("M9 21.25V16a3 3 0 0 1 6 0v5.25m-4.5-9.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ppnauzbbl {
  d: path("m12.79 4.12l6.67 5.26q.79.62.04.62t-.75 1v9.25q0 1-1 1H6.25q-1 0-1-1V11q0-1-.75-1t.04-.62l6.67-5.26q.79-.62 1.58 0");
}

</style>
