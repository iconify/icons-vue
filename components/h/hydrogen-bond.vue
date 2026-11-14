<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4lwe5but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hydrogen-bond" /></template>
<style>
.c4lwe5but {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5s3 4 3 8a3 3 0 0 1-6 0c0-4 3-8 3-8Zm14 0s3 4 3 8a3 3 0 0 1-6 0c0-4 3-8 3-8Zm-8.5 8h.01m2.99 0h.01");
}

</style>
