<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f22ajzb8t"/><path class="vhnbtvbtn"/><path class="x1w930bwh"/><path class="a_-b16kjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bus-outline-thin" /></template>
<style>
.a_-b16kjh {
  d: path("M15 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.f22ajzb8t {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.x1w930bwh {
  d: path("M5 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
