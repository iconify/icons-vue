<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d03yrbcko"/><path class="fe4hj_bmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ghost-net" /></template>
<style>
.d03yrbcko {
  d: path("M4 2.5h16L18.5 11q-6.5 4.5-13 0Zm5.5 0V13m5-10.5V13M4.75 7h14.5");
}

.fe4hj_bmu {
  d: path("M3 16.75q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0m-15.75 4q2.25-1.5 4.5 0t4.5 0t4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
