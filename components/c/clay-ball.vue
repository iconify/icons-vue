<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2iwn5byz"/><path class="y60ga1b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clay-ball" /></template>
<style>
.h2iwn5byz {
  d: path("M15.25 3.25a9.5 9.5 0 1 0 6 7a6 6 0 0 1-6-7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y60ga1b0n {
  d: path("M16 11.5a9 9 0 0 1-3.5-5");
}

</style>
