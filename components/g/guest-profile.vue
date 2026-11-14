<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="mtktsybpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-profile" /></template>
<style>
.hneliqdkn {
  d: path("M2.5 4h19v16h-19Z");
}

.mtktsybpv {
  d: path("M6.5 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.25 7.5c0-1.75 1.5-2.75 3.25-2.75s3.25 1 3.25 2.75M14.5 9h4.25m-4.25 3.5h4.25M14.5 16H17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
