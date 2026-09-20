<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dhm9wy0nm"/><path class="wy8f0maog"/><path class="pt0xyi7kd"/><path class="e6q34etyy"/><path class="dahw1rbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-precision-outline-bold" /></template>
<style>
.dahw1rbat {
  d: path("M18 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dhm9wy0nm {
  d: path("M3 5h10");
}

.e6q34etyy {
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.pt0xyi7kd {
  d: path("M3 17h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wy8f0maog {
  d: path("M3 11h10");
}

</style>
