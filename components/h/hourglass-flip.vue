<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sz_ac1bxn"/><path class="y58vo2-8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hourglass-flip" /></template>
<style>
.sz_ac1bxn {
  d: path("M5 3v2.5c0 2.5 2.5 5 4 6.5c-1.5 1.5-4 4-4 6.5V21h8v-2.5c0-2.5-2.5-5-4-6.5c1.5-1.5 4-4 4-6.5V3ZM3.5 3h11m-11 18h11M17 4.5a9 9 0 0 1 0 15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y58vo2-8x {
  d: path("M17.5 16.75L17 19.5l2.75.5");
}

</style>
