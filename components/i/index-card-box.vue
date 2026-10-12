<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="go4py7bii"/><rect class="yi810b21w"/><path class="wn5-dsdjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:index-card-box" /></template>
<style>
.go4py7bii {
  d: path("M6 8.5v-2A1.5 1.5 0 0 1 7.5 5h12.25a1.5 1.5 0 0 1 1.5 1.5v10a1.5 1.5 0 0 1-1.5 1.5h-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn5-dsdjt {
  d: path("M2.75 12.25h16m-13 3.25h10m-10 3h6");
}

.yi810b21w {
  width: 16px;
  height: 12.75px;
  x: 2.75px;
  y: 8.5px;
  rx: 2px;
}

</style>
