<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3912bc7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bunny-suit" /></template>
<style>
.y3912bc7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6a3.5 3.5 0 0 1 7 0l4 2l2 7H19l-2.25-4.5v11H13.5V15h-3v6.5H7.25v-11L5 15H2.5l2-7ZM12 8.75v3.5M7.25 19h3.25m3 0h3.25");
}

</style>
