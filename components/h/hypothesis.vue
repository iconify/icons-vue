<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dm6066bor"/><path class="d7oxkveve"/><path class="bvog_2vkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hypothesis" /></template>
<style>
.bvog_2vkr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.5h.01M4.5 20.25h.01");
}

.d7oxkveve {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 9.25a1.9 1.9 0 1 1 2.6 1.75c-.5.2-.85.6-.85 1.15v.35");
}

.dm6066bor {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 16.85a4 4 0 0 1-.55-7.96A5.75 5.75 0 0 1 16.85 7.5a4.5 4.5 0 0 1-.6 9.35Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
