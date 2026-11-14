<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fcn10p8ye"/><path class="xfqpozbou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-change-left" /></template>
<style>
.fcn10p8ye {
  d: path("M2.5 2.5v19m19-19v19M12 2.5v4m0 11v4m4 0V16c0-4-8-4-8-8V4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfqpozbou {
  d: path("M5.25 6.75L8 4l2.75 2.75");
}

</style>
