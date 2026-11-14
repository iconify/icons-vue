<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3-_yrljg"/><path class="j-uuwsbvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-withdrawal-slip" /></template>
<style>
.j-uuwsbvv {
  d: path("M14.9 12.5H8V9h8v3m-8 4h4m2.5 2a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm1.75 0h3.5");
}

.n3-_yrljg {
  d: path("M12.8 21.5H5v-19h14v9.3M8 6h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
