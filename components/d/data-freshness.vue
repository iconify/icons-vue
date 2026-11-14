<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4a4hjagh"/><path class="w5z5drbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-freshness" /></template>
<style>
.d4a4hjagh {
  d: path("M10.884 21.223C7.007 21.033 4 19.871 4 18.5v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.455");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5z5drbsa {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q1.001-.001 1.933-.082m.817 6.582c0-4.25 2.25-6.5 6.5-6.5c0 4.25-2.25 6.5-6.5 6.5Zm0 0l3.75-3.75");
}

</style>
