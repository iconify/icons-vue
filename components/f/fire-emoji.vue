<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0z4vgbdl"/><path class="h36uzdc9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-emoji" /></template>
<style>
.h36uzdc9x {
  d: path("M12 19a2.25 2.25 0 0 1-2.25-2.25c0-1.5 1-2.75 2.25-4.25c1.25 1.5 2.25 2.75 2.25 4.25A2.25 2.25 0 0 1 12 19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0z4vgbdl {
  d: path("M12 21.25a7 7 0 0 1-7-7c0-2.75.75-4.75 1.5-6.75c.5 1.75 1.25 2.75 2.5 3.25c0-3 1-5.75 3-8C14 5 15 7.25 15 10c1-.75 1.75-2 2.5-3.5c1 2 1.5 4.75 1.5 7.75a7 7 0 0 1-7 7");
}

</style>
