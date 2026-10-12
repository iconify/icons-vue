<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf8alac5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ci-pipeline-x-sharp" /></template>
<style>
.tf8alac5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5h4.5v5h-4.5zm7 0h4.5v5h-4.5zm7 0h4.5v5h-4.5zM7.25 15h2.5m4.5 0h2.5m-12-4.75V5.5h14.5v4.75M17.5 8.5l1.75 1.75L21 8.5");
}

</style>
