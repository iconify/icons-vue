<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hbamb061q"/><path class="wilanfbqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-arrow-right" /></template>
<style>
.hbamb061q {
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17m-12 5.25h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wilanfbqy {
  d: path("m13 12.75l2.5 2.5l-2.5 2.5");
}

</style>
