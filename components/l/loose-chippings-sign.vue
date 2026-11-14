<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zzbm4ab-k"/><path class="yc4y2ebhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loose-chippings-sign" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc4y2ebhc {
  fill: currentColor;
  d: path("M8 16a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm4-3.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm7.5-4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.zzbm4ab-k {
  d: path("M12 2.5L22 20H2Z");
}

</style>
