<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2nahlbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-dioxide" /></template>
<style>
.y2nahlbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.25 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm8.75 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.75 10.5h3.5m-3.5 3h3.5m5.5-3h3.5m-3.5 3h3.5");
}

</style>
