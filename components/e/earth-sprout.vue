<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qwgldg5km"/><path class="sn4_ctbzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-sprout" /></template>
<style>
.qwgldg5km {
  d: path("M5 15a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.sn4_ctbzs {
  d: path("M8.5 15a3.5 7 0 1 0 7 0a3.5 7 0 1 0-7 0ZM5 15h14m-7-7V5.5m0 0q.75-3 4.5-3q-.75 3-4.5 3Zm0 0q-.75-3-4.5-3q.75 3 4.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
