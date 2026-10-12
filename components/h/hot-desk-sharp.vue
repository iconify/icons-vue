<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xngo6fbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-desk-sharp" /></template>
<style>
.xngo6fbaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 4.75h9.5M15 3l1.75 1.75L15 6.5m1.75 3.75h-9.5M9 8.5l-1.75 1.75L9 12m-6.25 3h18.5v3H2.75zm2.75 3v3.25m13-3.25v3.25");
}

</style>
