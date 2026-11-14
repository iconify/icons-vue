<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5oz4tzth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funnel-dropoff" /></template>
<style>
.s5oz4tzth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.236 3.5h9.528a1.75 1.75 0 0 1 1.344 2.87l-3.452 4.143a1.75 1.75 0 0 0-.406 1.121v5.404A1.6 1.6 0 0 1 11 18.5l-1.211-.538a1.75 1.75 0 0 1-1.039-1.599v-4.729a1.75 1.75 0 0 0-.406-1.121L4.892 6.37A1.75 1.75 0 0 1 6.236 3.5M15.5 8.25h.01m2.49 5s-2.25 3-2.25 4.75a2.25 2.25 0 0 0 4.5 0c0-1.75-2.25-4.75-2.25-4.75");
}

</style>
