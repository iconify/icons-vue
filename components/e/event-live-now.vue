<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed31ulawk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-live-now" /></template>
<style>
.ed31ulawk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8.559 7.085a6 6 0 0 1 6.882 0m0 9.83a6 6 0 0 1-6.882 0M5.894 4.723a9.5 9.5 0 0 1 12.212 0m0 14.554a9.5 9.5 0 0 1-12.212 0");
}

</style>
