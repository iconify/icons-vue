<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tts6p6b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compare-products-sharp" /></template>
<style>
.tts6p6b0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h7.5V15.5h-7.5zM5 6.5h3m-3 3h3m5.75-6.75h7.5V15.5h-7.5zM16 6.5h3m-3 3h3M5.25 19.25h13.5M7.25 17.5l-2 1.75l2 1.75m9.5-3.5l2 1.75l-2 1.75");
}

</style>
