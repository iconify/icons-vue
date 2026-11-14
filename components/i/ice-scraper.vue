<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6rn4k03g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-scraper" /></template>
<style>
.e6rn4k03g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.616 3.788l4.596 4.596a1.75 1.75 0 0 1 0 2.475l-.353.353a1.75 1.75 0 0 1-2.475 0L9.788 6.616a1.75 1.75 0 0 1 0-2.475l.353-.353a1.75 1.75 0 0 1 2.475 0m-.58 5.176za1.5 1.5 0 0 1 0 2.122l-4.95 4.95a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l4.95-4.95a1.5 1.5 0 0 1 2.122 0M18.5 15.5v6M16 17l5 3m-5 0l5-3");
}

</style>
