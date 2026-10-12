<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owqi-mbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:log-cabin-sharp" /></template>
<style>
.owqi-mbsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.37 8.58l8.01-5.41l.62-.42l.62.42l8.01 5.41l.62.42H2.75zM5.5 12h13a1.54 1.54 0 0 1 0 3.08a1.54 1.54 0 0 1 0 3.09a1.54 1.54 0 0 1 0 3.08h-13a1.54 1.54 0 0 1 0-3.08a1.54 1.54 0 0 1 0-3.09a1.54 1.54 0 0 1 0-3.08Zm0 3.08h13m-13 3.09h13");
}

</style>
