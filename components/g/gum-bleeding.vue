<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky5y2jbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gum-bleeding" /></template>
<style>
.ky5y2jbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.79 14.935l.46-2.185C15.75 10.75 17 9 17 6.5c0-2.25-1-4-3-4c-1.5 0-2.5.75-4 .75S7.5 2.5 6 2.5c-2 0-3 1.75-3 4c0 2.5 1.25 4.25 1.75 6.25l1 4.75c.25 1 1.5 1 1.75 0l1-4.25C8.75 12.5 9.25 12 10 12s1.25.5 1.5 1.25l1 4.25c.111.445.421.692.752.741M19 14c1.5 1.75 3 3.5 3 4.75a3 3 0 0 1-6 0c0-1.25 1.5-3 3-4.75");
}

</style>
