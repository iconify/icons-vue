<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bymg9zg0o"/><path class="u4c1nbb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calendar-deadline" /></template>
<style>
.bymg9zg0o {
  d: path("M7.375 4h9.25A4.375 4.375 0 0 1 21 8.375v8.75a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.75A4.375 4.375 0 0 1 7.375 4M8 2.5v3m8-3v3m-13 3h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u4c1nbb_i {
  d: path("M10 18.5v-7h6l-1.5 2.25L16 16h-6");
}

</style>
