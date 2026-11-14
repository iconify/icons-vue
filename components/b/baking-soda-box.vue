<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="idb6ki-1y"/><path class="hqpnb7b7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baking-soda-box" /></template>
<style>
.hqpnb7b7t {
  d: path("M9 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.idb6ki-1y {
  d: path("M6 2.5h12v19H6Zm0 4h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
