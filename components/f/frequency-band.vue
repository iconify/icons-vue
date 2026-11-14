<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1513btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frequency-band" /></template>
<style>
.bg1513btn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12C4 7.5 5.75 7.5 7.25 12s3.25 4.5 4.75 0s3.25-4.5 4.75 0s3.25 4.5 4.75 0m-19-6.5h19m-19 13h19");
}

</style>
