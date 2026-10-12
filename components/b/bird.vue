<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wz3cr4bke"/><path class="x-_4otb8o"/><path class="gf3ajvb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bird" /></template>
<style>
.gf3ajvb1g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14.75c1.75 0 3.75-.75 5-2.25");
}

.wz3cr4bke {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 4.75a3.5 3.5 0 0 1 3.5 3.5V12c0 4.75-3.5 8.5-8.25 8.5H3.75c1-1 1.5-2 1.5-3.5c0-4 2.75-6.75 6-7.25v-1.5a3.5 3.5 0 0 1 3.5-3.5m3.75 2.5l2.75 1.25l-2.75 1.25Z");
}

.x-_4otb8o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 8h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
