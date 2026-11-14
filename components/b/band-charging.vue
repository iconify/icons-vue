<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt9oo9bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:band-charging" /></template>
<style>
.xt9oo9bkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6h8a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm2 0V2.5h4V6m-4 11v4.5h2.6m1.4-1.6V17m8.25-2.25L16 19h2.5l-1.25 3l4-4.5h-2.5Z");
}

</style>
