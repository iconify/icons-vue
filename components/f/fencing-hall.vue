<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ui0b6yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fencing-hall" /></template>
<style>
.p9ui0b6yl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20 2.5l-12 12m-4-12l11 11m-6-2l2 2m2 0l2-2m-.75 6.5L18 14.5l3.75 3.5v3.75h-7.5Z");
}

</style>
