<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ahwty1o-g"/><path class="j7qsoybds"/><path class="flxei0bpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guitar-strap" /></template>
<style>
.ahwty1o-g {
  d: path("M9 10.5a3.5 3.5 0 1 1 4.5 4.5A4.5 4.5 0 1 1 9 10.5m5.75-1.25L20.5 3.5");
}

.flxei0bpr {
  d: path("M7.5 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7qsoybds {
  d: path("M5.75 18.25C3 21 2 14 2.75 10C3.5 5.5 9 2.5 17.25 6.75");
}

</style>
