<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1sra3b_x"/><path class="xei74ni_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clarity" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1sra3b_x {
  d: path("m13.237 4.237l6.526 6.526a1.75 1.75 0 0 1 0 2.474l-6.526 6.526a1.75 1.75 0 0 1-2.474 0l-6.526-6.526a1.75 1.75 0 0 1 0-2.474l6.526-6.526a1.75 1.75 0 0 1 2.474 0");
}

.xei74ni_w {
  fill: currentColor;
  d: path("m9.439 5.561l-5.378 5.378a1.5 1.5 0 0 0 0 2.122l5.378 5.378A1.5 1.5 0 0 0 12 17.379V6.621a1.5 1.5 0 0 0-2.561-1.06");
}

</style>
