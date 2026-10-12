<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy8yy8wvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calorie-burn-sharp" /></template>
<style>
.gy8yy8wvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 21.25a5.5 5.5 0 0 1-5.5-5.5c0-3.25 2.5-5 3.25-8.75c1.75 1.25 2.75 2.75 2.75 4.5l1.364-.963l.236-1.887c2.15 1.6 3.4 4 3.4 7.1a5.5 5.5 0 0 1-5.5 5.5ZM19 3.75v8.5M16.75 10L19 12.25L21.25 10");
}

</style>
