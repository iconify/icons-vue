<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nthzy-03t"/><path class="w4g1icb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:enzyme-catalyst" /></template>
<style>
.nthzy-03t {
  d: path("M14.5 8.25V7.5c0-3-2.5-5-5.75-5c-4 0-6.25 4-6.25 9.5s2.25 9.5 6.25 9.5c3.25 0 5.75-2 5.75-5v-.75h-4v-7.5ZM17 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4g1icb0p {
  d: path("M13.25 13.75V12H17");
}

</style>
