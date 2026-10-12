<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se0-5fbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-year-sharp" /></template>
<style>
.se0-5fbva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Zm11 0q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Zm-14.75 14h18.5m-18.5-2.5v5m18.5-5v5");
}

</style>
