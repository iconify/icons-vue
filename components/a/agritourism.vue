<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4nlfabvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agritourism" /></template>
<style>
.w4nlfabvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v6M6 13v8.5m-2.5-13H16l2.25 2.25L16 13H3.5Zm2.5-6L10.5 4L6 5.5ZM18.75 17c-1.5-1.25-3.5-.5-3.5 1.75c0 2 1.75 3.5 3.5 2.75c1.75.75 3.25-.75 3.25-2.75c0-2.25-1.75-3-3.25-1.75Zm0 0l.75-1.75");
}

</style>
