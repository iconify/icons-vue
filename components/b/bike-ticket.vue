<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5jtr6bfk"/><path class="nmrtp2zzo"/><path class="h_q36tb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-ticket" /></template>
<style>
.f5jtr6bfk {
  d: path("M4.5 5H16a1.5 1.5 0 0 0 3 0h.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H19a1.5 1.5 0 0 0-3 0H4.5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2m13 4.25v5.5");
}

.h_q36tb2i {
  d: path("M7 13.5L10 9l3 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmrtp2zzo {
  d: path("M5 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
