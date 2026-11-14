<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqmqjc8ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cherry-blossom" /></template>
<style>
.uqmqjc8ud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 9.5A4.5 4.5 0 0 1 10 3.25l2 1.25l2-1.25a4.5 4.5 0 0 1-.25 6.25a4.5 4.5 0 0 1 6-2.25l-.5 2.5l1.75 1.5A4.5 4.5 0 0 1 14.75 13a4.5 4.5 0 0 1 4 5H16.5l-1 2.25A4.5 4.5 0 0 1 12 15a4.5 4.5 0 0 1-3.5 5.25L7.5 18H5.25a4.5 4.5 0 0 1 4-5A4.5 4.5 0 0 1 3 11.25l1.75-1.5l-.5-2.5a4.5 4.5 0 0 1 6 2.25ZM12 12h.01");
}

</style>
