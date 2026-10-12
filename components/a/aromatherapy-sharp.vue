<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4snbbbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aromatherapy-sharp" /></template>
<style>
.v4snbbbds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 10L7.773 8.375L9.25 6.75l1.477-1.625L9.25 3.5m5.5 6.5l-1.477-1.625L14.75 6.75l1.477-1.625L14.75 3.5M5.25 13h13.5l-1.1 6.6l-.298 1.676l-1.702-.026h-7.3l-1.702.026L6.35 19.6Zm3.25 3.75h7");
}

</style>
