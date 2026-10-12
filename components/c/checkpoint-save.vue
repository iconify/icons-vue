<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ay8zmdpxo"/><path class="ij-jo_u4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checkpoint-save" /></template>
<style>
.ay8zmdpxo {
  d: path("M4.5 6.75h6.25q1.75 0 2.99 1.24l.77.77q1.24 1.24 1.24 2.99v7.75q0 1.75-1.75 1.75H4.5q-1.75 0-1.75-1.75v-11q0-1.75 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ij-jo_u4y {
  d: path("M6 7v2.75h5M6 21v-4.25h6.5V21M18 7v6.75M18 3h3.25L20 5l1.25 2H18Z");
}

</style>
