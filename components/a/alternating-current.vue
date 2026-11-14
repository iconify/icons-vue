<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fny13vmsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alternating-current" /></template>
<style>
.fny13vmsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12c1.5-9.5 3.5-9.5 5 0s3.5 9.5 5 0M2.5 12h19M4.75 9.75L2.5 12l2.25 2.25m14.5-4.5L21.5 12l-2.25 2.25");
}

</style>
