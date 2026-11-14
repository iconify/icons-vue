<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzfq7ac1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:defrost-freezer" /></template>
<style>
.tzfq7ac1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5v11M3.25 5.25l9.5 5.5m0-5.5l-9.5 5.5M16.5 12s-3 3.5-3 5.75a3 3 0 0 0 6 0c0-2.25-3-5.75-3-5.75");
}

</style>
