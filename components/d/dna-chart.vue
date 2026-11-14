<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oidxa-2ga"/><path class="cm2ow8cxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dna-chart" /></template>
<style>
.cm2ow8cxc {
  d: path("M13 2.5C13 7.25 3 7.25 3 12c0 4.302 8.201 4.708 9.75 8.274M3 12h10m2.5 9.5v-3m3 3v-5m3 5v-7");
}

.oidxa-2ga {
  d: path("M3 2.5C3 7.25 13 7.25 13 12S3 16.75 3 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
