<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lnr-gu81x"/><path class="fjrc5kb2r"/><path class="nudc98b_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hallway" /></template>
<style>
.fjrc5kb2r {
  d: path("M9.5 7h5A1.5 1.5 0 0 1 16 8.5v7a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 15.5v-7A1.5 1.5 0 0 1 9.5 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lnr-gu81x {
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 4.25 2.5");
}

.nudc98b_u {
  d: path("M10.25 17v-7h3.5v7M2.5 2.5L8 7m13.5-4.5L16 7M2.5 21.5L8 17m13.5 4.5L16 17");
}

</style>
