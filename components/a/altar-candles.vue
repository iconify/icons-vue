<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ejco7teid"/><path class="s52cmhioc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:altar-candles" /></template>
<style>
.ejco7teid {
  d: path("M3.5 17.5v-7a8.5 8.5 0 0 1 17 0v7m-17 0h17M2.5 21h19");
}

.s52cmhioc {
  d: path("M7 17.5V13a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v4.5M8.5 6c1.25 1.25 1.5 2.25 0 3.25c-1.5-1-1.25-2 0-3.25ZM14 17.5V13a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v4.5M15.5 6c1.25 1.25 1.5 2.25 0 3.25c-1.5-1-1.25-2 0-3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
