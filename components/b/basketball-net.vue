<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="its0akbby"/><path class="yao28lupv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-net" /></template>
<style>
.its0akbby {
  d: path("M4 6a8 2.5 0 1 0 16 0A8 2.5 0 1 0 4 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yao28lupv {
  d: path("m4 6l3 13.5h10L20 6M8 8.5l6.5 11m1.5-11l-6.5 11");
}

</style>
