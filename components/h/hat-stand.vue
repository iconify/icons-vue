<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdgd3bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hat-stand" /></template>
<style>
.bzdgd3bhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 8l.5-3.75c1-1.75 6-1.75 7 0L16 8M3 8h18c-1.5 2-16.5 2-18 0Zm9 1.5V19m-4.5 2.5L12 19l4.5 2.5M8 6.25h8");
}

</style>
