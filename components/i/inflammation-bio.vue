<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4tyh2b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inflammation-bio" /></template>
<style>
.c4tyh2b-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5c2 0 3 1.5 4.5 1.5s1.5-7 5-7s3.5 7 5 7s2.5-1.5 4.5-1.5M5 21h14M12 8.25Q10.5 7.125 12 6c1-.75 1-1.5 0-2.5M7.5 9.25Q6 8.125 7.5 7t0-2.25m9 4.5Q15 8.125 16.5 7t0-2.25");
}

</style>
