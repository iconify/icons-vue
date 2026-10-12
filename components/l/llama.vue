<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="aw4c7bc6h"/><path class="njvf-ub1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:llama" /></template>
<style>
.aw4c7bc6h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.25c0-1.5 1-2.5 2.25-2.5l.5-2l1 1.75H9c1 0 1.75.75 1.75 1.75V12h7.5c1.75 0 3 1.25 3 3v5.25h-2.5V17h-6v3.25h-2.5V15.5C9 15.5 8 14.5 8 13V9.5H7c-1.25 0-2-1-2-2.25");
}

.njvf-ub1m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 6.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
