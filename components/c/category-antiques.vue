<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmcvteb1z"/><path class="y5wd3shxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-antiques" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5wd3shxq {
  d: path("M9.5 7c-6.5-2-7 7-2.25 7m7.25-7c6.5-2 7 7 2.25 7");
}

.zmcvteb1z {
  d: path("M8 3h8l-1.5 4c4 1.5 3.5 7.5.5 10.5l.5 3.5h-7l.5-3.5c-3-3-3.5-9 .5-10.5Z");
}

</style>
