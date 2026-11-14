<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bwiwx6b6g"/><path class="lacsvmmby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fitness-band" /></template>
<style>
.bwiwx6b6g {
  d: path("M5.5 6.5h13v11h-13Zm3-4v4m7-4v4m-7 11v4m7-4v4");
}

.lacsvmmby {
  d: path("M8.5 12h2l1.25-2.5l1.25 5l1.25-2.5h1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
