<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7ewwx5rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flask-round-sharp" /></template>
<style>
.t7ewwx5rr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.75h3v5.17a6.75 6.75 0 0 1 5.25 6.58H5.25a6.75 6.75 0 0 1 5.25-6.58ZM5.25 14.5h13.5a6.75 6.75 0 0 1-13.5 0ZM9 2.75h6");
}

</style>
