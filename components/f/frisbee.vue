<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="favjnacfq"/><path class="yri197b8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:frisbee" /></template>
<style>
.favjnacfq {
  d: path("M20.53 7.35a7.75 4.25-20 1 1-14.56 5.3a7.75 4.25-20 1 1 14.56-5.3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yri197b8r {
  d: path("M17.01 8.63a4 2-20 1 1-7.52 2.74a4 2-20 1 1 7.52-2.74M2.75 18l5.5-2m-3 5.25l5.5-2");
}

</style>
