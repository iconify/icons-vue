<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="msdkdobrv"/><path class="pxi6rsbqa"/><path class="yjk7dbbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ballot-paper-search" /></template>
<style>
.msdkdobrv {
  d: path("M14.4 21.5H3v-19h15v10");
}

.pxi6rsbqa {
  d: path("M6 5.5h7v7H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjk7dbbxf {
  d: path("m8.25 9l1.25 1.25L11 8m4.25 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
