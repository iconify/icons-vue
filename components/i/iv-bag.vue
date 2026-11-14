<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a24gnzrya"/><path class="d7wuwacqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:iv-bag" /></template>
<style>
.a24gnzrya {
  d: path("M10.75 2.5h2.5a5.25 5.25 0 0 1 5.25 5.25v5A5.25 5.25 0 0 1 13.25 18h-2.5a5.25 5.25 0 0 1-5.25-5.25v-5a5.25 5.25 0 0 1 5.25-5.25");
}

.d7wuwacqf {
  d: path("M10.75 5.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M8 9.5h2m-2 2.75h2M8 15h2m2 3v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
