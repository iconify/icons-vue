<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibh6n4b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:effort-level" /></template>
<style>
.ibh6n4b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.5h6.5A1.5 1.5 0 0 1 12 12a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 12A1.5 1.5 0 0 1 4 10.5m8 1.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7 0h2.5");
}

</style>
