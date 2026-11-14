<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekrc5bb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consumer" /></template>
<style>
.ekrc5bb4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5V19a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-5.5H16L14.5 16h-5L8 13.5Zm9.5-11V11M8.75 8L12 11.25L15.25 8");
}

</style>
