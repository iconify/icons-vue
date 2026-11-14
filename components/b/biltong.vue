<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7_-g6_md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biltong" /></template>
<style>
.f7_-g6_md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 6l2.5-1.5l2 1C11.5 10 10 15 12 19l-2.5 1.5l-2-1c-2-4-.5-9-3.5-13.5Zm8.5-2L15 3l2 1c3 4.5 1.5 9.5 3.5 13.5L18 19l-2-1c-2-4-.5-9-3.5-14Z");
}

</style>
