<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kzwqlgs3u"/><rect class="ygaqiu52c"/><path class="pg4xejb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loft-apartment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzwqlgs3u {
  d: path("M2.75 20.5V9.25q0-.75.61-1.19l4.95-3.62q.61-.44.61.31v3q0 .75.61.31l4.94-3.62q.61-.44.61.31v3q0 .75.61.31l4.95-3.62q.61-.44.61.31V20.5q0 .75-.75.75h-17q-.75 0-.75-.75");
}

.pg4xejb6q {
  d: path("M12 11.5v7M6.25 15h11.5");
}

.ygaqiu52c {
  width: 11.5px;
  height: 7px;
  x: 6.25px;
  y: 11.5px;
  rx: 1px;
}

</style>
