<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzsfsc11v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiddler-crab" /></template>
<style>
.yzsfsc11v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12.5h12V18H5Zm9 0l3-2.75C14.5 7.5 15.5 3 19 3c1.75 0 2.75 1.5 2.5 2.5l-2.75.5l2.75 1.75c-.75 2-2.75 2.75-4.5 2M8 12.5L5.5 9.75m4.25 2.75V10m2.75 2.5V10M5 15.5l-2.25 2m14.25-2l2.25 2M3 21h18");
}

</style>
