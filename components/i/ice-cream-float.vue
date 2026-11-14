<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yomqa9b0u"/><path class="ly3si1yhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-cream-float" /></template>
<style>
.ly3si1yhk {
  d: path("M7.75 8.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM6.5 15.5h11m-2 2l2-15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yomqa9b0u {
  d: path("m5.5 10l2 11.5h9l2-11.5");
}

</style>
