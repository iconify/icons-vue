<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izeczmu8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:acorn-sharp" /></template>
<style>
.izeczmu8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11v.75c0 4.5-2.5 8.25-5.5 9.5c-3-1.25-5.5-5-5.5-9.5ZM5 11c0-3 3-5 7-5s7 2 7 5Zm7-5V3.8l1.75-1.05");
}

</style>
