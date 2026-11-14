<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gb9a1se4g"/><path class="v339tjbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basket-produce-full" /></template>
<style>
.gb9a1se4g {
  d: path("M3 10h18l-2 10H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v339tjbaf {
  d: path("M5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm8 3c0-4 2-6.5 6-7c0 4-2 6.5-6 7Zm-4 3v4m6-4v4");
}

</style>
