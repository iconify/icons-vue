<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wrvqjebbm"/><path class="r_m0sh4sy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dock-slot" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r_m0sh4sy {
  d: path("M17.25 6.5za1.5 1.5 0 0 1 1.5 1.5v9a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V8a1.5 1.5 0 0 1 1.5-1.5M8 13h.01");
}

.wrvqjebbm {
  d: path("M16.5 2.5H18A3.5 3.5 0 0 1 21.5 6v12a3.5 3.5 0 0 1-3.5 3.5h-1.5A3.5 3.5 0 0 1 13 18V6a3.5 3.5 0 0 1 3.5-3.5M13 15.25a5.5 5.5 0 1 1 0-4.5");
}

</style>
