<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvbstf4et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-expand-all-sharp" /></template>
<style>
.mvbstf4et {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4.25L10 10M4 9V4h5m10.75 15.75L14 14m6 1v5h-5m4.75-15.75L14 10m1-6h5v5M4.25 19.75L10 14m-1 6H4v-5");
}

</style>
