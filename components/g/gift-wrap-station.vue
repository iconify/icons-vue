<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by2zieiyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-wrap-station" /></template>
<style>
.by2zieiyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5c-1-3-3.5-4.5-3.75-2.75C8 6.25 10.5 7.5 12 7.5Zm0 0c1-3 3.5-4.5 3.75-2.75C16 6.25 13.5 7.5 12 7.5Zm-5.5 0h11v3h-11Zm1 3v5m9-5v5m-4.5-5v5m-9.5 0h19v3h-19Zm2.5 3v3m14-3v3");
}

</style>
