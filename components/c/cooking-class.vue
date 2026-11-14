<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgvhnvbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cooking-class" /></template>
<style>
.sgvhnvbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12v7a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2v-7m-9 0c-3 0-3.5-4.5 0-5C8 4.25 11 3.5 12 5c1-1.5 4-.75 4.5 2c3.5.5 3 5 0 5Z");
}

</style>
