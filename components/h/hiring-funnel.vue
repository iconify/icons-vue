<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6i0ikbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hiring-funnel" /></template>
<style>
.y6i0ikbft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.923 8.5h8.154a1.729 1.729 0 0 1 1.173 3l-2.687 2.48A1.75 1.75 0 0 0 14 15.266v3.021a1.75 1.75 0 0 1-1.136 1.639L12 20.25a1.48 1.48 0 0 1-2-1.386v-3.598a1.75 1.75 0 0 0-.563-1.286L6.75 11.5a1.729 1.729 0 0 1 1.173-3M5 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
