<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0cttxqef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hanami-blossom-branch" /></template>
<style>
.s0cttxqef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5L15.25 7.25M8 15.75l-2-6.5m5.75 2l4.5 4.5m2.5-11a1.5 1.5 0 1 1 1 2.5a1.5 1.5 0 1 1-2.25 1.5a1.5 1.5 0 1 1-2.25-1.5a1.5 1.5 0 1 1 1-2.5a1.5 1.5 0 1 1 2.5 0Zm-11.5.5a1.5 1.5 0 1 1 1 2.5A1.5 1.5 0 1 1 6 9.25a1.5 1.5 0 1 1-2.25-1.5a1.5 1.5 0 1 1 1-2.5a1.5 1.5 0 1 1 2.5 0Zm11.5 10.5a1.5 1.5 0 1 1 1 2.5a1.5 1.5 0 1 1-2.25 1.5a1.5 1.5 0 1 1-2.25-1.5a1.5 1.5 0 1 1 1-2.5a1.5 1.5 0 1 1 2.5 0Z");
}

</style>
