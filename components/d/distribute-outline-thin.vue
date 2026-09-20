<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a4oza3fug"/><path class="gg6jr8oaf"/><path class="jlsc9oajw"/><path class="h3yzlbw2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distribute-outline-thin" /></template>
<style>
.a4oza3fug {
  d: path("M3 4v16");
}

.gg6jr8oaf {
  d: path("M21 4v16");
}

.h3yzlbw2w {
  d: path("M14 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlsc9oajw {
  d: path("M6 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

</style>
