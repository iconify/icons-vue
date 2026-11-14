<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn-1dxbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cac" /></template>
<style>
.tn-1dxbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.272 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.331 0 .653.018M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7.5 7h3.75l3.5 3.5L18 21.75l-3.5-3.5Zm2.25 2.25h.01");
}

</style>
