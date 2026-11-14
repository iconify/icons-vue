<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dezw4qb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gum" /></template>
<style>
.dezw4qb1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5V8a3 3 0 0 1 6 0a3 3 0 0 1 6 0a3 3 0 0 1 6 0v6.5m-18 0q3 3.5 6 0q3 3.5 6 0q3 3.5 6 0V20H3ZM9 8v6.5M15 8v6.5");
}

</style>
