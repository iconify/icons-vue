<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="symzxcowd"/><path class="i3x23cctd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heating-mantle" /></template>
<style>
.i3x23cctd {
  d: path("M3 12.5a9 9 0 0 0 18 0");
}

.symzxcowd {
  d: path("M10.5 2.5v6a5.25 5.25 0 1 0 3 0v-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
