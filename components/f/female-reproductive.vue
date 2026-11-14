<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brues2i6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:female-reproductive" /></template>
<style>
.brues2i6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9c0-1 1-1.5 3.5-1.5s3.5.5 3.5 1.5c0 3.5-1.5 6-2.25 7.5v4h-2.5v-4C10 15 8.5 12.5 8.5 9Zm0-.25C7 5.5 4.5 5 3.5 8m12 .75C17 5.5 19.5 5 20.5 8m-18 3.75a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0Zm15.5 0a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0Z");
}

</style>
