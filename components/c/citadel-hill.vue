<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hhzzfhlue"/><path class="x81y27bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:citadel-hill" /></template>
<style>
.hhzzfhlue {
  d: path("M2.5 21h19m-19 0c3.5-5.5 15.5-5.5 19 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x81y27bap {
  d: path("M5.5 18.25V4H9v7h1.75V9h2.5v2H15V4h3.5v14.25");
}

</style>
