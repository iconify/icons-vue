<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h01r_5fde"/><path class="tai9yxj4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:denture-cleaner" /></template>
<style>
.h01r_5fde {
  d: path("m4.5 3l2 18h11l2-18");
}

.tai9yxj4a {
  d: path("M8.5 14.5c0 4.5 7 4.5 7 0M8 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
