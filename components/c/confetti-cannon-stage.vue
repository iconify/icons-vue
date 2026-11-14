<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2brc_bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:confetti-cannon-stage" /></template>
<style>
.k2brc_bfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l4-10.5l6.5 6.5ZM9 3l1.5 3m4 1.5h.01m2.49-4l2.5 1m-1.5 6l3 1m-2.5 4h.01");
}

</style>
