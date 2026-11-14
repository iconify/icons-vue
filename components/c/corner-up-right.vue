<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qq_8n4bqv"/><path class="yanhvrmwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corner-up-right" /></template>
<style>
.qq_8n4bqv {
  d: path("M4.5 19.5V13A3.5 3.5 0 0 1 8 9.5h11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yanhvrmwg {
  d: path("m14.5 4.5l5 5l-5 5");
}

</style>
