<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5u7ep_9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-edger" /></template>
<style>
.v5u7ep_9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01M10.25 12l8.25-8.25M17 2.5l3.25 3.25M2.5 21.5h19m-6.5 0v-3m3 3V18");
}

</style>
