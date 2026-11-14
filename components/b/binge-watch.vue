<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aqzwtl29x"/><path class="g0h4fbcxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:binge-watch" /></template>
<style>
.aqzwtl29x {
  d: path("M2.5 9h19v12.5h-19Zm2-3h15m-13-3h11");
}

.g0h4fbcxk {
  d: path("m10 12l5 3.25l-5 3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
