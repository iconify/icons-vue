<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cl2-2t2rm"/><path class="y7f1inb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:long-temple-horn" /></template>
<style>
.cl2-2t2rm {
  d: path("M4.5 20c3-1.5 5-4 5.5-7.5l1-8l-.75-2.5h3.5L13 4.5l1 8c.5 3.5 2.5 6 5.5 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7f1inb-x {
  d: path("M4.5 20a7.5 1.5 0 1 0 15 0a7.5 1.5 0 1 0-15 0");
}

</style>
