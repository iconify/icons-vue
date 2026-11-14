<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsij89ufg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cooler-bag" /></template>
<style>
.lsij89ufg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h17V21h-17Zm0 3h17M8 7.5v-2A1.5 1.5 0 0 1 9.5 4h5A1.5 1.5 0 0 1 16 5.5v2m-4 6V18m1.949-3.375l-3.898 2.25m3.898 0l-3.898-2.25");
}

</style>
