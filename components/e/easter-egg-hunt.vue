<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7-8jcbqe"/><path class="damxvg8lo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:easter-egg-hunt" /></template>
<style>
.b7-8jcbqe {
  d: path("M12 2.5c4.5 0 7 6.5 7 11.5c0 4.5-3 7.5-7 7.5s-7-3-7-7.5C5 9 7.5 2.5 12 2.5");
}

.damxvg8lo {
  d: path("m5.25 12l2.25-2l2.25 2L12 10l2.25 2l2.25-2l2.25 2M5.5 16.5l2-2l2.25 2l2.25-2l2.25 2l2.25-2l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
