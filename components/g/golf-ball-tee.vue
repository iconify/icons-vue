<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cud9bvb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-ball-tee" /></template>
<style>
.cud9bvb4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a6 6 0 1 0 12 0A6 6 0 1 0 6 8Zm1.5 9h9L13 19v2.5h-2V19ZM10 6.75h.01m3.74 2.5h.01");
}

</style>
