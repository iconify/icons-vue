<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfvii0b5s"/><path class="yvoouxbhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bakery-in-store" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfvii0b5s {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v7a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 13V6A3.5 3.5 0 0 1 7 2.5m-2.065 14h14.13a1.75 1.75 0 0 1 1.716 1.407l.3 1.5a1.75 1.75 0 0 1-1.716 2.093H4.635a1.75 1.75 0 0 1-1.716-2.093l.3-1.5A1.75 1.75 0 0 1 4.935 16.5");
}

.yvoouxbhk {
  d: path("M7.5 13c0-5 9-5 9 0Z");
}

</style>
