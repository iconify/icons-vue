<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxs3okbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-strip-frames" /></template>
<style>
.mxs3okbor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h16v19H4Zm4.5 0v19m7-19v19M8.5 9h7m-7 6h7M6.25 5.75V6m0 5.75V12m0 5.75V18m11.5-12.25V6m0 5.75V12m0 5.75V18");
}

</style>
