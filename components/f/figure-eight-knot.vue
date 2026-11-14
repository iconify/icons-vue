<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy1amglqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:figure-eight-knot" /></template>
<style>
.fy1amglqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c3-3 3.75-9 0-9s-3 6 0 9s3.75 9 0 9s-3-6 0-9Zm2.5-5.5L19 3M9.5 17.5L5 21");
}

</style>
