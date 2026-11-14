<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ittx7xbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chest-of-drawers" /></template>
<style>
.ittx7xbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5V5q0-2 2-2h14q2 0 2 2v14.5Zm2 0v2m14-2v2M3 8.5h18M3 14h18M10 5.75h4m-4 5.5h4m-4 5.5h4");
}

</style>
