<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j67ny5bkf"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-waiting" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.j67ny5bkf {
  d: path("M21 5v3.5L16.5 10L15 8c-2.5 1-6 4.5-7 7l2 1.5L8.5 21H5a2 2 0 0 1-2-2c.5-8.5 7.5-15.5 16-16a2 2 0 0 1 2 2Zm-6.25 13a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
