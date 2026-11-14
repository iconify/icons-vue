<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0d1fygka"/><path class="myeclem6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:full-body-workout" /></template>
<style>
.f0d1fygka {
  d: path("M10 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myeclem6u {
  d: path("m2.5 6l9.5 4l9.5-4M12 10v4.5m-6.5 7l6.5-7l6.5 7");
}

</style>
