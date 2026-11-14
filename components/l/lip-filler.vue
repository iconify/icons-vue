<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l-v78srpg"/><path class="gcp_1d4tw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lip-filler" /></template>
<style>
.gcp_1d4tw {
  d: path("M2.5 8.5q9.5 2.5 19 0m-2.439 6.318l2.121 2.121l-3.536 3.536l-2.121-2.121Zm1.06 1.061l1.415-1.415m-4.95 4.95l-1.061 1.061m-.884-.884l1.768 1.768");
}

.l-v78srpg {
  d: path("M18.203 11.77C16.252 13.095 14.227 13.5 12 13.5c-3.5 0-6.5-1-9.5-5C5 4.5 8 3 10 4l2 1.25L14 4c2-1 5 .5 7.5 4.5c-.766 1.021-1.531 1.846-2.305 2.509");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
