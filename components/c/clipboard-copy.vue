<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kmeqglalm"/><rect class="s8e5_8bzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clipboard-copy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmeqglalm {
  d: path("M8.75 4.25h-1.5a2.5 2.5 0 0 0-2.5 2.5v12a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5v-12a2.5 2.5 0 0 0-2.5-2.5h-1.5");
}

.s8e5_8bzb {
  width: 6.5px;
  height: 3.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
