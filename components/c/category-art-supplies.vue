<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy30xozzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-art-supplies" /></template>
<style>
.sy30xozzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c-5 0-8.5 3.5-8.5 8c0 4 3 5.5 5 5s2 1.5 2 2.5c0 1.5 1 1.75 1.75 1.75c5.25 0 8.25-3.75 8.25-8.75S17 3.5 12 3.5M8 9h.01M12 7h.01M16 9h.01");
}

</style>
