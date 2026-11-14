<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a95ub6bhf"/><path class="mkkxf___a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:judo-scoreboard" /></template>
<style>
.a95ub6bhf {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkkxf___a {
  d: path("M7 7.25h1.75A1.75 1.75 0 0 1 10.5 9v2.5a1.75 1.75 0 0 1-1.75 1.75H7a1.75 1.75 0 0 1-1.75-1.75V9A1.75 1.75 0 0 1 7 7.25m8.25 0H17A1.75 1.75 0 0 1 18.75 9v2.5A1.75 1.75 0 0 1 17 13.25h-1.75a1.75 1.75 0 0 1-1.75-1.75V9a1.75 1.75 0 0 1 1.75-1.75m-10 9.25h13.5");
}

</style>
