<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cptk-kfky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:distance-run" /></template>
<style>
.cptk-kfky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12.5C5 11 3 8.75 3 6.5a3.5 3.5 0 0 1 7 0c0 2.25-2 4.5-3.5 6Zm11 3.5C16 14.5 14 12.25 14 10a3.5 3.5 0 0 1 7 0c0 2.25-2 4.5-3.5 6Zm-11-.75c0 5.75 11 5.75 11 3.75");
}

</style>
