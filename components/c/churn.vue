<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcwf6_bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:churn" /></template>
<style>
.wcwf6_bca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.772 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.357 0 2.612.229 3.691.647M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM14.5 18h6.75m-2.75-2.75L21.25 18l-2.75 2.75");
}

</style>
