<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i6zktx90d"/><path class="wdn-7oz5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cave" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6zktx90d {
  d: path("m2.75 21.25l2-9.25c1-4.75 3.75-7.25 7.25-7.25s6.25 2.5 7.25 7.25l2 9.25Z");
}

.wdn-7oz5l {
  d: path("M8.25 21.25V17.5a3.75 3.75 0 0 1 7.5 0v3.75m-11.5-3.5q1.125-.75 2.25 0");
}

</style>
