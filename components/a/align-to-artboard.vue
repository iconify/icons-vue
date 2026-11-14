<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvr-uoklt"/><path class="ajmeehv7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:align-to-artboard" /></template>
<style>
.ajmeehv7u {
  d: path("M5.5 5.5h6v6h-6Z");
}

.fvr-uoklt {
  d: path("M5.5 2.5v19m-3-16h19m-16 0h15v15h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
