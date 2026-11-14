<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6hkr_b3v"/><path class="jxa8v5bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garage-unit" /></template>
<style>
.h6hkr_b3v {
  d: path("m2.5 9.5l9.5-6l9.5 6M3.5 9v12.5M20.5 9v2.8m-8.1 9.7H5.5V11h8v1.4m-8 1.6h6.9m-6.9 3h6.9M8 19.5h3m4.25-4.25h6.25v6.25h-6.25Z");
}

.jxa8v5bhe {
  d: path("m17.5 17.5l1-.75v2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
