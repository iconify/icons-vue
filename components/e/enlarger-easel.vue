<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k3ih7ybiu"/><path class="sdup-wboq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:enlarger-easel" /></template>
<style>
.k3ih7ybiu {
  d: path("M3 3h18v13H3Zm3 13l-1.5 4M18 16l1.5 4");
}

.sdup-wboq {
  d: path("M6.5 6.5h11v6h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
