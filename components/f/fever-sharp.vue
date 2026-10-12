<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aamelab0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fever-sharp" /></template>
<style>
.aamelab0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 12.75V5a2.25 2.25 0 0 1 4.5 0v7.75a4.25 4.25 0 1 1-4.5 0ZM9 7v8.5m6.5-8.75c-1 1 1 2.25 0 3.25s1 2.25 0 3.25m4-6.5c-1 1 1 2.25 0 3.25s1 2.25 0 3.25");
}

</style>
