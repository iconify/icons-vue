<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im1mdrbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inbox-lock" /></template>
<style>
.im1mdrbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h5l1.5 2.5h5L16 12h5v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm6-6h6v4.5H9Zm1.25 0V4.75a1.75 1.75 0 0 1 3.5 0V6");
}

</style>
