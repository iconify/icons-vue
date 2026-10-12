<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5d1t8i8v"/><rect class="w-tvq90-l"/><path class="h5z-_1oop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-saw" /></template>
<style>
.e5d1t8i8v {
  d: path("m9.25 6.5l11.25 4.6a1.25 1.25 0 0 1 .75 1.15V16l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5Z");
}

.h5z-_1oop {
  d: path("M5.5 9.75V14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-tvq90-l {
  width: 6.75px;
  height: 12.5px;
  x: 2.75px;
  y: 5.5px;
  rx: 2.5px;
}

</style>
