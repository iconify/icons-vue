<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mbf2pm3_i"/><path class="h149zeb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-pin" /></template>
<style>
.h149zeb_v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 14.75h.01m8.99 0h.01");
}

.mbf2pm3_i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5L5.6 7.1a2 2 0 0 1 1.9-1.35h9a2 2 0 0 1 1.9 1.35l1.85 5.4v4.75a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1Zm2.75 5.75v2.5m11-2.5v2.5m-13.25-9.5h15.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
