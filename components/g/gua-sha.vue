<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymjwmqylt"/><path class="zqpiu-bgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gua-sha" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymjwmqylt {
  d: path("M6.04 9.4c3.45-1.26 5.69 1.83 8.56.51c1.43-.69 1.78-2.04 2.92-2.74a2.1 2.1-20 0 1 2.42 3.59q-.8.85-1.28 1.86q-.92-.22-1.39.79q-.92-.23-1.39.78q-.92-.22-1.39.79c-1.36 1.61-3.25 2.58-5.22 3.3A4.73 4.73-20 0 1 6.04 9.4");
}

.zqpiu-bgj {
  d: path("M9 12.75c2 1.15 4 1.25 5.5.5");
}

</style>
