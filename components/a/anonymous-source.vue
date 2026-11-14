<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zfqqr8bin"/><path class="xhxohloia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anonymous-source" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhxohloia {
  d: path("M9 11a3 3.75 0 1 0 6 0a3 3.75 0 1 0-6 0Z");
}

.zfqqr8bin {
  d: path("M3.5 21.5V20c0-2.5 1.5-4 2.5-4.5V10c0-4 3-6.5 6-7.5c3 1 6 3.5 6 7.5v5.5c1 .5 2.5 2 2.5 4.5v1.5Z");
}

</style>
