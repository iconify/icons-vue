<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6ep-qvao"/><path class="pmo02cy9m"/><path class="pz92bfbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:language-switch" /></template>
<style>
.l6ep-qvao {
  d: path("m3 11l3-7l3 7M4.25 8.5h3.5M15 13h6m-3 0v8m-2.5-4h5m-9-12.5H16a2 2 0 0 1 2 2V9");
}

.pmo02cy9m {
  d: path("m16 7.5l2 2l2-2m-7.5 12H8a2 2 0 0 1-2-2V15");
}

.pz92bfbaf {
  d: path("m4 16.5l2-2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
