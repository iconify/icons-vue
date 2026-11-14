<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twpwblbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flowchart-code" /></template>
<style>
.twpwblbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h3.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 8.25 7h-3.5A2.25 2.25 0 0 1 2.5 4.75A2.25 2.25 0 0 1 4.75 2.5m8.311 7.311l1.128 1.128a1.5 1.5 0 0 1 0 2.122l-1.128 1.128a1.5 1.5 0 0 1-2.122 0l-1.128-1.128a1.5 1.5 0 0 1 0-2.122l1.128-1.128a1.5 1.5 0 0 1 2.122 0M15.75 17h3.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-3.5a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 15.75 17M6.5 7v5h2.25m6.5 0h2.25v5");
}

</style>
