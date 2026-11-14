<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l74y4acmz"/><path class="rmvdxdb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:certification-badge" /></template>
<style>
.l74y4acmz {
  d: path("M18 9.5a3 3 0 0 1-1.75 4.25A3 3 0 0 1 12 15.5a3 3 0 0 1-4.25-1.75A3 3 0 0 1 6 9.5a3 3 0 0 1 1.75-4.25A3 3 0 0 1 12 3.5a3 3 0 0 1 4.25 1.75A3 3 0 0 1 18 9.5Z");
}

.rmvdxdb4u {
  d: path("m9.5 9.5l1.75 1.75L14.5 8m-5 7.25L8.25 21.5l2.25-1.25m4-5l1.25 6.25l-2.25-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
