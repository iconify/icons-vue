<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcuqz4brf"/><path class="c-81trboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:id-card-lanyard" /></template>
<style>
.bcuqz4brf {
  d: path("M6 7.5h12a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-7A3.5 3.5 0 0 1 6 7.5m3.5 0V5.25a2.5 2.5 0 0 1 5 0V7.5");
}

.c-81trboj {
  d: path("M6.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-.75 6.5c0-1.25 1.1-2 2.5-2s2.5.75 2.5 2m3-6.5h5m-5 4H17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
