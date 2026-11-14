<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w94t462nl"/><path class="vfuxv9bxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-christmas-club" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfuxv9bxs {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m-1.5-3C10.75 2.75 8 2 8 4c0 1 2 1.75 4 1.5m0 0C13.25 2.75 16 2 16 4c0 1-2 1.75-4 1.5");
}

.w94t462nl {
  d: path("M4 12c0-3.5 3.5-6 8-6s8 2.5 8 6c0 2.25-1.25 4-3.5 5v2.5H14v-1.75c-.75.25-1.25.25-2 .25s-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12");
}

</style>
