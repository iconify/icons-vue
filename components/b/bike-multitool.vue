<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnenvvbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-multitool" /></template>
<style>
.fnenvvbcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12za3 3 0 0 1 3 3v3.5a3 3 0 0 1-3 3a3 3 0 0 1-3-3V15a3 3 0 0 1 3-3M5.5 3A2.5 2.5 0 1 1 3 5.5m4.25 1.75L12 12m0 0V3.5h2.25M12 12l6.5-6.5M17 4l3 3m-8 8h.01");
}

</style>
