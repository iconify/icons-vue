<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nocjvskhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automatic-feeder" /></template>
<style>
.nocjvskhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h10v4L14 9h-4L7 6.5ZM3.5 17.75h17c0 2.25-1.5 3.75-4 3.75h-9c-2.5 0-4-1.5-4-3.75Zm8.5-6V15m-2.25-2.25L12 15l2.25-2.25");
}

</style>
