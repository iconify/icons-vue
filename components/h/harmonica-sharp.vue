<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7gexuvie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harmonica-sharp" /></template>
<style>
.i7gexuvie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h18.5v8.5H2.75zm0 2.5h18.5m-18.5 3.5h18.5M6 11.5v1m3.25-1v1m3.25-1v1m3.25-1v1m3.25-1v.01");
}

</style>
