<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n8nhn6p-f"/><path class="l74kskbph"/><path class="r8i1ocbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-wifi" /></template>
<style>
.l74kskbph {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.29 13.54a5.25 5.25 0 0 1 7.42 0m-5.65 1.77a2.75 2.75 0 0 1 3.88 0");
}

.n8nhn6p-f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75L12 3.25l8.25 6.5v8.5a2 2 0 0 1-2 2H5.75a2 2 0 0 1-2-2Z");
}

.r8i1ocbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
