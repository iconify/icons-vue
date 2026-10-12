<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fooyj_bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brain-scan" /></template>
<style>
.fooyj_bob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V5A2.25 2.25 0 0 1 5 2.75h2.5m9 0H19A2.25 2.25 0 0 1 21.25 5v2.5m0 9V19A2.25 2.25 0 0 1 19 21.25h-2.5m-9 0H5A2.25 2.25 0 0 1 2.75 19v-2.5m9.25-9c-.6-1-1.7-1.5-2.9-1.25a2.6 2.6 0 0 0-2 2.25a2.6 2.6 0 0 0-1.1 4a2.6 2.6 0 0 0 1.5 3.75A2.6 2.6 0 0 0 10.75 18c.5.4.8.5 1.25.5s.75-.1 1.25-.5a2.6 2.6 0 0 0 3.25-1.75A2.6 2.6 0 0 0 18 12.5a2.6 2.6 0 0 0-1.1-4a2.6 2.6 0 0 0-2-2.25C13.7 6 12.6 6.5 12 7.5m0 0v11m-7.25-6h14.5");
}

</style>
