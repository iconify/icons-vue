<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzjj0bfty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cleaning-service" /></template>
<style>
.bzjj0bfty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5V13a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5ZM5.5 8V4.5a1 1 0 0 1 1-1H12L14 5l-2 1.5V8ZM7 8v3m3-3v3m8.25 0c0 2.25 1 3.25 3.25 3.25c-2.25 0-3.25 1-3.25 3.25c0-2.25-1-3.25-3.25-3.25c2.25 0 3.25-1 3.25-3.25Z");
}

</style>
