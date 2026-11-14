<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgqy479zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-lesson" /></template>
<style>
.cgqy479zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-1.5 15V17a4.5 4.5 0 0 1 9 0v4.5m4.25-8.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-1.5 8.75a3.75 3.75 0 0 1 7.5 0M11.5 17l2-8");
}

</style>
