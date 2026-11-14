<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzvfg-bfy"/><path class="zfw37gb2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-appointment" /></template>
<style>
.gzvfg-bfy {
  d: path("M3.5 4.5h17v17h-17Zm4.5-2V6m8-3.5V6M3.5 8h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfw37gb2p {
  d: path("M10 12.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7 21.5c0-2.5 2.25-4 5-4s5 1.5 5 4");
}

</style>
