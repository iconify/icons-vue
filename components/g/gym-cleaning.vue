<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmvqsm49s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gym-cleaning" /></template>
<style>
.xmvqsm49s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11h2a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 4 18v-3.5A3.5 3.5 0 0 1 7.5 11M6 11V5a1.5 1.5 0 0 1 1.5-1.5h7V7h-4v4m.75-4l1.25 2M18 3.5h.01m2.49 2.25h.01M18 8h.01");
}

</style>
