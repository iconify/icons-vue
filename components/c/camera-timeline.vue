<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k8g0vix5z"/><path class="ars37pbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-timeline" /></template>
<style>
.ars37pbxm {
  d: path("M10.25 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.k8g0vix5z {
  d: path("M3.5 7A1.5 1.5 0 0 1 5 5.5h2L8.5 3h7L17 5.5h2A1.5 1.5 0 0 1 20.5 7v6a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 13ZM3 19.5h18m-6-2.25v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
