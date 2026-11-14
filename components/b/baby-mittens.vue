<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7jtruu3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-mittens" /></template>
<style>
.y7jtruu3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 16.5v-10a2.5 2.5 0 0 0-5 0v3c-1.5-.25-2.25.75-2.25 2c0 1.5 1.25 2.75 2.25 3.5v1.5m1.25 0h2.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8.5 20H6a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 6 16.5m8.25 0v-10a2.5 2.5 0 0 1 5 0v3c1.5-.25 2.25.75 2.25 2c0 1.5-1.25 2.75-2.25 3.5v1.5m-3.75 0H18a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18 20h-2.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75m-5.25 1.75q1.75 2 3.5 0");
}

</style>
