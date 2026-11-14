<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8i4dqbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blob" /></template>
<style>
.w8i4dqbhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c3 0 7 4 8 6s0 7.25-1.5 8s-3.5 4-5.5 4s-5.5-1-7-2.5s-3-4.5-3-7s3-3 4.5-4.5S9 3 12 3Zm-1 9.5h.01");
}

</style>
