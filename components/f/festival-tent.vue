<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lk8u8k3wy"/><path class="x9cv2hk7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:festival-tent" /></template>
<style>
.lk8u8k3wy {
  d: path("m2.5 20.5l9.5-13l9.5 13Zm9.5-18v5m0-5L15.5 4L12 5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9cv2hk7p {
  d: path("M8.5 20.5L12 13l3.5 7.5");
}

</style>
