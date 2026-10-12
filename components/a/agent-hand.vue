<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax7-frhmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-hand" /></template>
<style>
.ax7-frhmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 15.25v-6.5a1.5 1.5 0 0 1 3 0V12m0-3.25V6a1.5 1.5 0 0 1 3 0v6m0-5a1.5 1.5 0 0 1 3 0v5m0-2.5a1.5 1.5 0 0 1 3 0V15A6.25 6.25 0 0 1 15 21.25h-2a5.5 5.5 0 0 1-4.1-1.85l-4.3-4.8a1.5 1.5 0 0 1 2.3-1.95l2.35 2.6m-4-12.5q.3 2.2 2.5 2.5q-2.2.3-2.5 2.5q-.3-2.2-2.5-2.5q2.2-.3 2.5-2.5");
}

</style>
