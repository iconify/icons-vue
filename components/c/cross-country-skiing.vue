<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w76keffup"/><path class="i3nyh2u6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cross-country-skiing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3nyh2u6l {
  d: path("m14.75 7.5l-4.25 4.75l2.25 3.5L12 20.5m-1.5-8.25L8 16l-3.25 3M14 8.5l4.5 2l-4 8.75M14 8.5l-5.5.25l-5 8.25m6 4.25h7M2.75 20.5l4.5.75");
}

.w76keffup {
  cx: 16px;
  cy: 4.75px;
  r: 2px;
}

</style>
