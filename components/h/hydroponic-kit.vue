<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jf1ob6bit"/><path class="brt_rab3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hydroponic-kit" /></template>
<style>
.brt_rab3n {
  d: path("M6 17q1.5-1 3 0t3 0t3 0t3 0m-6-8.5V19m0-10.5c0-2.5-2-4-5-4c0 2.5 2 4 5 4m0 0c0-2.5 2-4 5-4c0 2.5-2 4-5 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf1ob6bit {
  d: path("M6.5 12.5h11A3.5 3.5 0 0 1 21 16v1.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5V16a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
