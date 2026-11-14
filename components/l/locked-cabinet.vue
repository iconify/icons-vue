<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bxm1o-bbz"/><path class="jlx9d0b5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:locked-cabinet" /></template>
<style>
.bxm1o-bbz {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5m4 0v3.7m0 13.1v2.2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlx9d0b5d {
  d: path("M10.75 12h2.5A1.75 1.75 0 0 1 15 13.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 14.75v-1A1.75 1.75 0 0 1 10.75 12m-.25 0v-1.5a1.5 1.5 0 0 1 3 0V12");
}

</style>
