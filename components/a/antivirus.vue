<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctmcg-tip"/><path class="qll7aiypa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antivirus" /></template>
<style>
.ctmcg-tip {
  d: path("m12 2.5l7.5 2.75V11c0 5-3.25 8.5-7.5 10.5c-4.25-2-7.5-5.5-7.5-10.5V5.25Z");
}

.qll7aiypa {
  d: path("M9.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.25-1.75l1-1m-1 4.5l1 1m-4.5-4.5l-1-1m1 4.5l-1 1m5.25-2.75H16m-6.5 0H8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
