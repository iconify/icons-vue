<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6x-bob4w"/><path class="dtt5tg88g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:few-shot" /></template>
<style>
.dtt5tg88g {
  d: path("M6 9.5v-4a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2H18M6 15.25h6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x6x-bob4w {
  d: path("M6 9.5h8.5A3.5 3.5 0 0 1 18 13v4.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5V13A3.5 3.5 0 0 1 6 9.5");
}

</style>
