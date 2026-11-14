<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-k-0abxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bookkeeper" /></template>
<style>
.s-k-0abxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 20.5c0-4 3-6.5 7.25-6.5c.899 0 1.799.202 2.516.425m4.484-.925h2.5a1.75 1.75 0 0 1 1.75 1.75v5A1.75 1.75 0 0 1 19.75 22h-2.5a1.75 1.75 0 0 1-1.75-1.75v-5a1.75 1.75 0 0 1 1.75-1.75m.25 2.75h2m-2 3h.01m1.99 0h.01");
}

</style>
