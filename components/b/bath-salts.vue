<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a5449nb5w"/><path class="yx-rdrb5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bath-salts" /></template>
<style>
.a5449nb5w {
  d: path("M3 12.5h18c0 5-4 8.5-9 8.5s-9-3.5-9-8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yx-rdrb5v {
  d: path("m10.389 10.686l.925-4.318a1.5 1.5 0 0 1 1.036-1.123l2.915-.875a1.5 1.5 0 0 1 1.787.795l1.485 3.136a1.5 1.5 0 0 1 .116.936l-.412 2.057A1.5 1.5 0 0 1 16.77 12.5h-4.915a1.5 1.5 0 0 1-1.466-1.814M10.75 9L6.5 8L5 12.5");
}

</style>
