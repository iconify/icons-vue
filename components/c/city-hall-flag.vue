<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eqq61ephd"/><path class="qvksdrblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:city-hall-flag" /></template>
<style>
.eqq61ephd {
  d: path("M3 21v-8.5h5.5v-4h7v4H21V21M2.5 21h19M12 8.5v-6m1.5 0H15A1.5 1.5 0 0 1 16.5 4A1.5 1.5 0 0 1 15 5.5h-1.5A1.5 1.5 0 0 1 12 4a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qvksdrblk {
  d: path("M10 21v-3.5a2 2 0 0 1 4 0V21");
}

</style>
