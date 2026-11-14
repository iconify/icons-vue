<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k85-qeb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compliance-officer" /></template>
<style>
.k85-qeb4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.072 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.895 0 1.746.1 2.532.288M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10 8.5H20a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 20 21h-3.5a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75m.5 2.75h2.5");
}

</style>
