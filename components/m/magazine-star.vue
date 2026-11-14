<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdcyjv09i"/><path class="tk_4lpbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magazine-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tk_4lpbod {
  d: path("m12.625 10.875l.261.574a1.5 1.5 0 0 0 1.241.874l.623.052a.698.698 0 0 1 .436 1.189l-.585.585a1.5 1.5 0 0 0-.395 1.425l.169.676a.617.617 0 0 1-.929.67l-.641-.408a1.5 1.5 0 0 0-1.61 0l-.641.408a.617.617 0 0 1-.929-.67l.169-.676a1.5 1.5 0 0 0-.395-1.425l-.585-.585a.698.698 0 0 1 .436-1.189l.623-.052a1.5 1.5 0 0 0 1.241-.874l.261-.574a.687.687 0 0 1 1.25 0");
}

.xdcyjv09i {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5m-.5 4h9");
}

</style>
