<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twtf33p9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-cold" /></template>
<style>
.twtf33p9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.037 0 2.015.134 2.901.384M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M18 14.75v6.5m-2.75-4.75l5.5 3m-5.5 0l5.5-3");
}

</style>
