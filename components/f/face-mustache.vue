<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2rvwuu_o"/><path class="vstff3h6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face-mustache" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2rvwuu_o {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 9h.01M15 9h.01");
}

.vstff3h6x {
  d: path("M12 13.5C10.5 12 8 12 7 14c-.5 1-1.25 1-1.75 0C5.5 16.5 8 17.25 10 16c1-.5 1.5-1 2-1s1 .5 2 1c2 1.25 4.5.5 4.75-2c-.5 1-1.25 1-1.75 0c-1-2-3.5-2-5-.5");
}

</style>
