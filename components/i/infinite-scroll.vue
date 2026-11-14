<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjv0-qbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:infinite-scroll" /></template>
<style>
.mjv0-qbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5c-1.25-1.75-2.5-3-4.5-3a3 3 0 0 0 0 6c2 0 3.25-1.25 4.5-3s2.5-3 4.5-3a3 3 0 0 1 0 6c-2 0-3.25-1.25-4.5-3m-3.5 7L12 20l3.5-3.5");
}

</style>
