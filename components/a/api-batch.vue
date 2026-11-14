<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o00l46bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-batch" /></template>
<style>
.o00l46bwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h12V7h-12Zm0 7.25h12v4.5h-12Zm0 7.25h12v4.5h-12Zm-3-14.5c-2 0-2 1-2 3V10c0 1.5-1 2-2 2c1 0 2 .5 2 2v4.5c0 2 0 3 2 3");
}

</style>
