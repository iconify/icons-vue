<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z4bw5qtpe"/><path class="z6z49eb0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feed-refresh" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4bw5qtpe {
  d: path("M20.5 12.5A8.5 8.5 0 1 1 12 4");
}

.z6z49eb0j {
  d: path("M10.25 2.25L12 4l-1.75 1.75M8 8.5h8v8H8Zm2.75 4h2.5");
}

</style>
