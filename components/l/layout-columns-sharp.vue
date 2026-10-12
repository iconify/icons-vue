<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3n0ggkzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layout-columns-sharp" /></template>
<style>
.e3n0ggkzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h4.17v16.5H2.75zm7.17 0h4.16v16.5H9.92zm7.16 0h4.17v16.5h-4.17z");
}

</style>
