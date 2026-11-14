<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqz3trbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greenest-route" /></template>
<style>
.tqz3trbbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 19c-2.5-3-3.5-4.5-3.5-6a3.5 3.5 0 0 1 7 0c0 1.5-1 3-3.5 6Zm11.5-7C15 9 14 7.5 14 6a3.5 3.5 0 0 1 7 0c0 1.5-1 3-3.5 6ZM6 19c6.5 0 5-7 11.5-7M6 13h.01M17.5 6h.01m-2.26 15.25c0-4 2-6 6.25-6c0 4-2 6-6.25 6Zm0 0L19 17.5");
}

</style>
