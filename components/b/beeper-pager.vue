<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pnfy28b3y"/><path class="egdh_n1ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beeper-pager" /></template>
<style>
.egdh_n1ye {
  d: path("M6 10h12v6H6Zm2.5 3H13");
}

.pnfy28b3y {
  d: path("M3 7h18v13H3Zm14.5-3.5V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
