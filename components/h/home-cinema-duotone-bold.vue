<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b46x6x-hs"/><path class="e03sywmba"/><path class="jaoga6bck"/><path class="cl583ybqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-cinema-duotone-bold" /></template>
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

.jaoga6bck {
  d: path("M5 20a3 3 0 0 1 6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
