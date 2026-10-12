<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p25d9g_id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cycling-helmet-sharp" /></template>
<style>
.p25d9g_id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.25h-1.5v-1.5c0-5.5 4.75-9 10.25-9c4.5 0 7.25 3 7.25 6.75c0 2-1.5 3.75-3.5 3.75ZM7.25 11l2-2.5m1.75 2L12.75 8m2 3l1.5-2.25M7 15.25l2.75 4.5l3.5-4.5");
}

</style>
