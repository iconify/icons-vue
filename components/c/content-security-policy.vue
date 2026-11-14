<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="scopxobpc"/><path class="xfbp8mbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:content-security-policy" /></template>
<style>
.scopxobpc {
  d: path("M12.8 20H2.5V3h19v9.3m0 6.9v.8h-.8M2.5 7h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfbp8mbor {
  d: path("M8.5 10L6 12.5L8.5 15m3.5-5l2.5 2.5L12 15m2.75 3l2 2L21 15.75");
}

</style>
