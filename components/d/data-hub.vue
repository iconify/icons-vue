<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="filbmacyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-hub" /></template>
<style>
.filbmacyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M12 2.5v3.75M10.25 4.5L12 6.25l1.75-1.75M12 21.5v-3.75m-1.75 1.75L12 17.75l1.75 1.75M2.5 12h3.75M4.5 10.25L6.25 12L4.5 13.75m17-1.75h-3.75m1.75-1.75L17.75 12l1.75 1.75");
}

</style>
