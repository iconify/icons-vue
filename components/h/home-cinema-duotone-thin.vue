<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b46x6x-hs"/><path class="e03sywmba"/><path class="jaoga6bck"/><path class="cl583ybqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-cinema-duotone-thin" /></template>
<style>
.b46x6x-hs {
  fill: currentColor;
  d: path("M3 4v10h18V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cl583ybqk {
  d: path("M13 20a3 3 0 0 1 6 0");
}

.e03sywmba {
  d: path("M3 4v10h18V4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jaoga6bck {
  d: path("M5 20a3 3 0 0 1 6 0");
}

</style>
