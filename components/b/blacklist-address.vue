<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iuz4k68jh"/><path class="o4-e0nbwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blacklist-address" /></template>
<style>
.iuz4k68jh {
  d: path("M8.9 5h12.6v12.6M15.1 19H2.5V6.4");
}

.o4-e0nbwg {
  d: path("M15.5 8H19v3.5h-3.5Zm-10 7.5H10m-6.5-12l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
