<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf-ez7bmu"/><path class="mmge5mg2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-sample" /></template>
<style>
.mmge5mg2s {
  d: path("M9 18c0-2.75 1.25-4 3-4s3 1.25 3 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf-ez7bmu {
  d: path("M7 3h10v3H7ZM6 8.75h12V21.5H6Z");
}

</style>
