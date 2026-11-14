<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y9gvcmbly"/><path class="ne9-c3blp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:action-item-add" /></template>
<style>
.ne9-c3blp {
  d: path("m5.5 8.5l1.75 1.75L9.75 7m5.75 1.5h6M18 15v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9gvcmbly {
  d: path("M2.5 3.5h10v10h-10Z");
}

</style>
