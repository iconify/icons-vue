<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh9seibwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:experiment-queue" /></template>
<style>
.sh9seibwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.5h2V9L7 16H2.5l1.25-7Zm7.25 0h2V9l1.25 7h-4.5L11 9Zm7.25 0h2V9l1.25 7H17l1.25-7ZM2.5 19.5h19");
}

</style>
