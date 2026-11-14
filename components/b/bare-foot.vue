<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yqvuyloei"/><path class="mpduvac-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bare-foot" /></template>
<style>
.mpduvac-a {
  d: path("M11.25 2.5V10c0 2 1 3.5 2.75 4.5m0 0q1.5-.75 2.5.75q1.5-.5 2.5 1.25q1.75.5 2 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yqvuyloei {
  d: path("M7 2.5v10c-2 1-3.5 3-3.5 5.5c0 1.75 1.25 3 3 3h12.75c1.25 0 2-1 1.75-2.25");
}

</style>
