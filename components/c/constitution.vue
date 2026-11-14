<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zxblkv2yz"/><path class="v-lbt-bba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:constitution" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-lbt-bba {
  d: path("M10 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.zxblkv2yz {
  d: path("M7 6.5h-.5a2 2 0 0 1 0-4h11a2 2 0 0 1 0 4H17V19a2.5 2.5 0 0 1-2.5 2.5h-8a2 2 0 0 1 0-4H7Zm2.5 3h5m-5 3h3");
}

</style>
