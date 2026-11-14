<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyfi46gbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beach-sunbed" /></template>
<style>
.hyfi46gbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7.5l3.5 7h13m-12.25 0V20m9.5-5.5V20M2.5 21.5q9.5-4 19 0M15 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-2V2.5m1.25 3.25L20 4m-1 3h2.5m-5.75-1.25L14 4m1 3h-2.5");
}

</style>
