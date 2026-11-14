<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jzk8b7bok"/><path class="hbeazbfpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fishing-vest" /></template>
<style>
.hbeazbfpk {
  d: path("M6.25 12h3v3h-3Zm8.5 0h3v3h-3Zm-8.5 5.5h3m5.5 0h3");
}

.jzk8b7bok {
  d: path("M8.5 3L11 9v12H5.5a1 1 0 0 1-1-1V6Zm7 0L13 9v12h5.5a1 1 0 0 0 1-1V6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
