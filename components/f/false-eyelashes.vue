<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cw_9hwbkv"/><path class="i_kqjkwwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:false-eyelashes" /></template>
<style>
.cw_9hwbkv {
  d: path("M3 15.25q9-10 18 0m-18 0q9 6.75 18 0");
}

.i_kqjkwwu {
  d: path("M7.5 11.5C6.75 9.25 6 8 4.5 7.25m7.5 3c0-2.25 0-3.5.75-5m3.75 6.25c.75-2.25 1.5-3.5 3-4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
