<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvi21nb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beta" /></template>
<style>
.uvi21nb0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5v-14a3.5 3.5 0 0 1 7 0c0 2-1.5 3.5-4 3.5c4 0 6.5 1.5 6.5 4.5c0 2.5-2 4-4.5 4c-2 0-4-.75-5-2");
}

</style>
