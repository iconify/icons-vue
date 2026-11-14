<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj8ts0bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:family" /></template>
<style>
.oj8ts0bjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM3.5 20.5V12a3 3 0 0 1 6 0v8.5m5 0V12a3 3 0 0 1 6 0v8.5m-10-8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5 3v5");
}

</style>
