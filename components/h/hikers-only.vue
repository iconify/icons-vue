<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-7u7qd8j"/><path class="ip6h5vbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hikers-only" /></template>
<style>
.e-7u7qd8j {
  d: path("M3.5 10.5a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0M12 19v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip6h5vbqo {
  d: path("M11.75 6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m.5 3.25l-.75 3M9.25 15l2.25-2.75L13.75 15M9.5 11.25l2.5-1l2.25 1.5");
}

</style>
