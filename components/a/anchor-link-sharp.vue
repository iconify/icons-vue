<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arwky1txz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anchor-link-sharp" /></template>
<style>
.arwky1txz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3.75L6 13.25m6-9.5l-1.25 9.5m-7-6.5h9.5m-10 4h9.5M15.5 14h-1a3 3 0 0 0 0 6h1m1.75-6h1a3 3 0 0 1 0 6h-1m-2.5-3H18");
}

</style>
