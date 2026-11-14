<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz8fecbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:in-store-sampling" /></template>
<style>
.zz8fecbws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5h18c-.5 2.75-4 4.5-9 4.5s-8.5-1.75-9-4.5m3-4h1A1.5 1.5 0 0 1 8.5 14v1A1.5 1.5 0 0 1 7 16.5H6A1.5 1.5 0 0 1 4.5 15v-1A1.5 1.5 0 0 1 6 12.5m5.5 0h1A1.5 1.5 0 0 1 14 14v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 15v-1a1.5 1.5 0 0 1 1.5-1.5m5.5 0h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5m-10.5 0L5 7.5m7 5v-6m5.5 6l1.5-5");
}

</style>
