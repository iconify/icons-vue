<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ity8po92l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:draw-search-area" /></template>
<style>
.ity8po92l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 20l.75-3.25L18.5 11l2.5 2.5l-5.75 5.75Zm.75-3.25l2.5 2.5m2-7l2.5 2.5m-10.5 3.5L7.5 17M5 15.25L3 14l.25-2m.25-2l.25-2m.5-2l.25-2.5L7 3.25M9 3l2-.25m1.5 0L15 2.5l1.75 1.75m1.5 1.5l1.5 1.5");
}

</style>
