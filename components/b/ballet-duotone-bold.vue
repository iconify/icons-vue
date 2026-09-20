<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g4xz9kbvt"/><path class="yya5lpbze"/><path class="i79bw0b_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ballet-duotone-bold" /></template>
<style>
.g4xz9kbvt {
  fill: currentColor;
  d: path("M3 18c0 -6 3 -9 7 -9 5 0 9 3.5 10 7 0.5 1.5 0 2 -2 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i79bw0b_m {
  d: path("M10 9C9 6 7 5 5 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yya5lpbze {
  d: path("M3 18c0 -6 3 -9 7 -9 5 0 9 3.5 10 7 0.5 1.5 0 2 -2 2Z");
}

</style>
