<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh12xwjtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:citrus-press-sharp" /></template>
<style>
.bh12xwjtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 11c0-4 2.4-7.4 5.25-8.25C14.85 3.6 17.25 7 17.25 11Zm3.5 0V8.5m3.5 2.5V8.5M3.25 14h17.5c0 4-3 7.25-7 7.25h-3.5c-4 0-7-3.25-7-7.25Z");
}

</style>
