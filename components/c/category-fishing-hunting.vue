<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g01zlll3k"/><path class="ws-h3nd9i"/><path class="fm-d68bwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-fishing-hunting" /></template>
<style>
.fm-d68bwr {
  d: path("M20 3.5V10m0 0v6.5a3.5 3.5 0 0 1-7 0V14m0 0l2 1.75");
}

.g01zlll3k {
  d: path("M3 21Q7 7 20 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ws-h3nd9i {
  fill: currentColor;
  d: path("M2.75 17a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
