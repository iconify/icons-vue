<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jczetxbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hourly-room" /></template>
<style>
.jczetxbif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h7v3C11.25 9 8.5 9.75 8.5 12s2.75 3 2.75 6.5v3h-7v-3C4.25 15 7 14.25 7 12S4.25 9 4.25 5.5Zm-1.5 0h10m-10 19h10M16 15.25v6.25m0-2.5h6v2.5m-4.25-5.25h2.75V19h-2.75Z");
}

</style>
