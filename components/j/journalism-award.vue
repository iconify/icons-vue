<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfzd08f0w"/><path class="grvyc2b8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:journalism-award" /></template>
<style>
.grvyc2b8q {
  d: path("M7 5.5H5.5a2.5 2.5 0 0 0 0 5h1.75m9.75-5h1.5a2.5 2.5 0 0 1 0 5h-1.75m-4.75 3V18m-2.75 0h5.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 9.25 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfzd08f0w {
  d: path("M7 3.5h10v5a5 5 0 0 1-10 0Z");
}

</style>
