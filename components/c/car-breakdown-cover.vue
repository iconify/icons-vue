<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxjaj9bbc"/><path class="f5_d5rn3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-breakdown-cover" /></template>
<style>
.f5_d5rn3e {
  d: path("M4.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.821 5.203l.988 1.836a1.5 1.5 0 0 1-1.32 2.211h-1.978a1.5 1.5 0 0 1-1.32-2.211l.988-1.836a1.5 1.5 0 0 1 2.642 0M18 18v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxjaj9bbc {
  d: path("M4.5 12h-2V8.5A1.5 1.5 0 0 1 4 7h1l2.5-4.5H14L17 7h2a2 2 0 0 1 2 2v3h-5.5m-4 0h-3");
}

</style>
