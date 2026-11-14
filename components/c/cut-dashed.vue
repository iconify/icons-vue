<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eph6i3b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cut-dashed" /></template>
<style>
.eph6i3b6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm0 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.75-7.75L15 15m-7.75.25L15 9m3 3h.01m3.49 0h.01");
}

</style>
