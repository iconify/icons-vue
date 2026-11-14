<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8dn3ybhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat" /></template>
<style>
.s8dn3ybhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17c-2-2 2-4.5 0-6.5S9 6 7 4m5 13c-2-2 2-4.5 0-6.5S14 6 12 4m5 13c-2-2 2-4.5 0-6.5S19 6 17 4M3 20.5h18");
}

</style>
