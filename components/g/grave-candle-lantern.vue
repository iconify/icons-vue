<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mzzjlibuf"/><path class="y63x6l_bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grave-candle-lantern" /></template>
<style>
.mzzjlibuf {
  d: path("m5.5 8.5l6.5-6l6.5 6Zm1.5 0h10v10H7Zm-2 10h14v3H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y63x6l_bj {
  d: path("M12 11.25c2.25 2 2.5 4 0 4.5c-2.5-.5-2.25-2.5 0-4.5Z");
}

</style>
