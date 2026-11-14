<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm8thtocz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-sent" /></template>
<style>
.cm8thtocz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h17v4.5h-17ZM5 12.5v7A1.5 1.5 0 0 0 6.5 21H12m0-13v13m0-13c-1.5-3-5-5-5.25-2.25C6.6 7.25 9 8 12 8m0 0c1.5-3 5-5 5.25-2.25C17.4 7.25 15 8 12 8m3 10h6m-2.5-2.5L21 18l-2.5 2.5");
}

</style>
