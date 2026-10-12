<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ywppwfrrh"/><path class="c1ofi6nid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drop-off-point" /></template>
<style>
.c1ofi6nid {
  d: path("M4.25 16.25h15.5M12 2.75v8.5m-3.5-3.5l3.5 3.5l3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywppwfrrh {
  width: 15.5px;
  height: 7.5px;
  x: 4.25px;
  y: 13.75px;
  rx: 1.25px;
}

</style>
