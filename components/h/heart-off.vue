<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5yyk-9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-off" /></template>
<style>
.oz5yyk-9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.35 18.348A29 29 0 0 1 12 20S3 14.5 3 8.75c0-.529.084-1.037.239-1.51m4.689-3.237C9.608 4.069 11.131 5.051 12 6.5C12.9 5 14.5 4 16.25 4C18.9 4 21 6.1 21 8.75c0 2.008-1.097 3.985-2.526 5.709M3.5 3.5l17 17");
}

</style>
