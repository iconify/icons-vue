<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qduorgbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:load-bearing-wall" /></template>
<style>
.qduorgbas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11h13a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 4 20v-7.5A1.5 1.5 0 0 1 5.5 11M4 15.5L8.5 11M4 20l9-9M7 21.5L17.5 11m-6 10.5L20 13m-4 8.5l4-4M7 2.5v6M5.5 7L7 8.5L8.5 7M12 2.5v6M10.5 7L12 8.5L13.5 7M17 2.5v6M15.5 7L17 8.5L18.5 7");
}

</style>
