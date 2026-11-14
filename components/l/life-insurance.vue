<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cl-o831pm"/><path class="bbps8srzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:life-insurance" /></template>
<style>
.bbps8srzg {
  d: path("m12 8.5l3 1v2c0 1.8-1.25 2.8-3 3.5c-1.75-.7-3-1.7-3-3.5v-2Z");
}

.cl-o831pm {
  d: path("M12 20S3 14.5 3 8.75C3 6.1 5.1 4 7.75 4C9.5 4 11.1 5 12 6.5C12.9 5 14.5 4 16.25 4C18.9 4 21 6.1 21 8.75C21 14.5 12 20 12 20Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
