<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih6g9hs5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-spiral" /></template>
<style>
.ih6g9hs5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c0-1.5 2-1.5 2 .5c0 2.5-3.5 3-4.5.5c-1.5-3.5 2.5-6 6-4.5c4 2 3.5 8.5-1.5 10.5c-5.5 2-10.5-2.5-10-7.5s5-8 9-8");
}

</style>
