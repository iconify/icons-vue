<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4s2crwhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:funnel-sharp" /></template>
<style>
.q4s2crwhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75h17.5l-.37.93l-.64 1.64l-.37.93H4.13l-.37-.93l-.64-1.64l-.37-.93zm2.56 6.5h12.38l-.37.93l-.64 1.64l-.37.93H6.69l-.37-.93l-.64-1.64l-.37-.93zm2.56 6.5h7.26l-.37.93l-.64 1.64l-.37.93h-5.5l-.37-.93l-.64-1.64l-.37-.93z");
}

</style>
