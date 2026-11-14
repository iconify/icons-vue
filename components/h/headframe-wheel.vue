<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dad3i6b9n"/><path class="j_k5utbyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headframe-wheel" /></template>
<style>
.dad3i6b9n {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.j_k5utbyv {
  d: path("m5.5 21.5l6.5-14l6.5 14M7 7.5h10m0 0v14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
