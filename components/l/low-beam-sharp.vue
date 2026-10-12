<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-40s633g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:low-beam-sharp" /></template>
<style>
.f-40s633g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.5c-3.9 0-7 2.9-7 6.5s3.1 6.5 7 6.5h1.75v-13zm5 1l6.5 2m-6.5 2l6.5 2m-6.5 2l6.5 2");
}

</style>
