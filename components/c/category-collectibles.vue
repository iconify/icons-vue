<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xt0q3gb5x"/><path class="rt4x7ubkm"/><path class="ia7if0gqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-collectibles" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ia7if0gqt {
  d: path("m16.058 11.606l.207.503a1.5 1.5 0 0 0 1.273.924l.541.042a.604.604 0 0 1 .345 1.062l-.413.352a1.5 1.5 0 0 0-.486 1.496l.128.528a.604.604 0 0 1-.904.656l-.462-.285a1.5 1.5 0 0 0-1.574 0l-.462.285a.604.604 0 0 1-.904-.656l.128-.528a1.5 1.5 0 0 0-.486-1.496l-.413-.352a.604.604 0 0 1 .345-1.062l.541-.042a1.5 1.5 0 0 0 1.273-.924l.207-.503a.604.604 0 0 1 1.116 0");
}

.rt4x7ubkm {
  d: path("M12.375 7h6.25a2.625 2.625 0 0 1 2.625 2.625v9.25a2.625 2.625 0 0 1-2.625 2.625h-6.25a2.625 2.625 0 0 1-2.625-2.625v-9.25A2.625 2.625 0 0 1 12.375 7");
}

.xt0q3gb5x {
  d: path("M9.75 20.5L6 21.5L2.25 7l10.5-2.75L13.5 7");
}

</style>
