<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2konmjoo"/><path class="buv_wrbqr"/><path class="ox8thhbkk"/><path class="kptcbybdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:elderly-crossing-sign" /></template>
<style>
.buv_wrbqr {
  d: path("M5.25 6.25Q4 9.5 4.5 13.25L2.75 21m1.75-7.75L6.25 21m10-16.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.h2konmjoo {
  d: path("M4.75 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kptcbybdf {
  d: path("m16 9.5l4.5 2.5v9");
}

.ox8thhbkk {
  d: path("M16.75 6.25q-1.25 3.25-.75 7L14.25 21M16 13.25L17.75 21M4.5 9.5L9 12v9");
}

</style>
