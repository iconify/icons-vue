<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="alw6hccxn"/><circle class="mhd4ugusn"/><circle class="f6q4dkbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coffee-plant" /></template>
<style>
.alw6hccxn {
  d: path("M3 9.75q9-1.5 18 0m-13-.6v5.35m8-5.35v7.35M6 9.33V6m8 3.04V5.75M6 6q4 1.44 4.75-2.75Q6.75 1.81 6 6m8-.25q3.89 1.63 4.75-2.5q-3.89-1.63-4.75 2.5");
}

.f6q4dkbbu {
  cx: 16px;
  cy: 18.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhd4ugusn {
  cx: 8px;
  cy: 16.75px;
  r: 2.25px;
}

</style>
