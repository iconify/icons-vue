<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui1bfccmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:day-night-cycle" /></template>
<style>
.ui1bfccmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 6a6 6 0 0 0 0 12Zm0 0a6 6 0 0 1 0 12a8 8 0 0 0 0-12ZM3 12h2.25m2.5-6.25l-1.5-1.5m1.5 14l-1.5 1.5");
}

</style>
