<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rm4evybhx"/><path class="r_8zyfb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brand-launch" /></template>
<style>
.r_8zyfb7l {
  d: path("M8.5 10.5H5l-1.75 2H6.5Zm5 5V19l-2 1.75V17.5Zm0-6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-6 8.5l-3 3");
}

.rm4evybhx {
  d: path("M6.5 12.5L13 6c2-2 5-2.5 7.5-2.5C20.5 6 20 9 18 11l-6.5 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
