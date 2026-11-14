<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghscb99sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corn-stalk" /></template>
<style>
.ghscb99sk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5v19M15 3c3 2 3.75 7 2.75 12h-5.5C11.25 10 12 5 15 3ZM5.5 18.5c3.5 0 5.5-1 6.75-3.5M15 3v12m-2.75-7.5h5.5m-6 4h6.5M5.5 13c-2.5-1.5-3-4-3-7");
}

</style>
