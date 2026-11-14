<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ztg16cc0w"/><path class="nkda28rnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:launch-tower" /></template>
<style>
.nkda28rnc {
  d: path("M3.5 7L8 11.5L3.5 16M8 6.5h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztg16cc0w {
  d: path("M3.5 21V3H8v18m7-18c2.5 2 3 5 3 8v7h-6v-7c0-3 .5-6 3-8ZM2.5 21h19");
}

</style>
