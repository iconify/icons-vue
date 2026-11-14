<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvsw12b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feed-bag" /></template>
<style>
.gvsw12b5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 7l-2 12.25a2 2 0 0 0 2 2.25h11a2 2 0 0 0 2-2.25L17.5 7M5 2.5h14V7H5Zm7 16v-8m0 2.5l-2-2m2 2l2-2m-2 5.5l-2-2m2 2l2-2");
}

</style>
