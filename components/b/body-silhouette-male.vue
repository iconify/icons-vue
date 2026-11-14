<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqof6ybsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-silhouette-male" /></template>
<style>
.eqof6ybsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5 5h7c1.5 0 2.5 1 2.75 2.5l1 5l-2 .25L16 13v8.5h-3V16h-2v5.5H8V13l-1.25 4.25l-2-.25l1-5C6 10.5 7 9.5 8.5 9.5Z");
}

</style>
