<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i65i8_fzx"/><rect class="k-j7vtahe"/><path class="c4h6qmb4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kiosk" /></template>
<style>
.c4h6qmb4j {
  d: path("M10.75 14.25h2.5q.5 0 .58.49l.59 3.52q.08.49-.42.49h-4q-.5 0-.42-.49l.59-3.52q.08-.49.58-.49m-4 7h10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i65i8_fzx {
  width: 12.5px;
  height: 11.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2px;
}

.k-j7vtahe {
  width: 7.5px;
  height: 5.5px;
  x: 8.25px;
  y: 5.25px;
  rx: 1px;
}

</style>
