<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9n6mbc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:attendee-remove" /></template>
<style>
.n9n6mbc5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3.5 21c0-4 3.5-6.5 7.5-6.5c1.293 0 2.533.261 3.62.75M15 18h6");
}

</style>
