<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwg2gbbad"/><path class="vxjsg5brh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farm-stay" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwg2gbbad {
  d: path("m3.249 9.584l2.455-4.09a1.75 1.75 0 0 1 .827-.715l4.796-1.999a1.75 1.75 0 0 1 1.346 0l4.796 1.999a1.75 1.75 0 0 1 .827.715l2.455 4.09a1.75 1.75 0 0 1 .249.901v8.765A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25v-8.765a1.75 1.75 0 0 1 .249-.901");
}

.vxjsg5brh {
  d: path("M8 21v-8h8v8m-8-8l8 8m0-8l-8 8");
}

</style>
