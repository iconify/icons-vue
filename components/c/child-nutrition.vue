<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bcpxpnbwz"/><path class="pqv5tc6_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-nutrition" /></template>
<style>
.bcpxpnbwz {
  d: path("M2.25 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.pqv5tc6_w {
  d: path("M5.25 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm4.5 0V7.5m0 4.5l3.75 2.5M9.75 12L6 14.5M18.75 6a1.5 2.5 0 1 0 3 0a1.5 2.5 0 1 0-3 0Zm1.5 2.5v12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
