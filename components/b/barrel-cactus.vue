<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_cwt4ehc"/><path class="wezf8qb9y"/><path class="jg-m0xb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barrel-cactus" /></template>
<style>
.g_cwt4ehc {
  d: path("M5 14.5C4 12 4 8 6.5 6c2-1.75 9-1.75 11 0C20 8 20 12 19 14.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg-m0xb5o {
  d: path("M12 5v9.5M8.75 5c-1 3-1 6.5-.25 9.5M15.25 5c1 3 1 6.5.25 9.5M12 4.75V2.5m-5 3L5.25 3.75M17 5.5l1.75-1.75");
}

.wezf8qb9y {
  d: path("M7.518 14.5h8.964a1.75 1.75 0 0 1 1.733 1.997l-.5 3.5a1.75 1.75 0 0 1-1.733 1.503H8.018a1.75 1.75 0 0 1-1.733-1.503l-.5-3.5A1.75 1.75 0 0 1 7.518 14.5");
}

</style>
