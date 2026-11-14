<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jku_m-b7r"/><path class="llg14tr0f"/><path class="q470p7bic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyword-match" /></template>
<style>
.jku_m-b7r {
  d: path("M14.3 21.5H4.5v-19h15v10.8m0 7.9v.3h-.3M8 6h8");
}

.llg14tr0f {
  fill: currentColor;
  d: path("M8 9.25h6.5v2.25H8Z");
}

.q470p7bic {
  d: path("M8 14.75h6.1M8 18.25h3m3.75-.25l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
