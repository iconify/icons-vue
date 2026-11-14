<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cupxpbbwt"/><path class="n1xq85s5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bridal-makeup" /></template>
<style>
.cupxpbbwt {
  d: path("M13 16.4v5.1H5V12h8v3.8M6.5 12V6.5l5-3.5v9m4.5 7.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.n1xq85s5v {
  d: path("m17 15.75l1.5-1.5l1.5 1.5l-1.5 1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
