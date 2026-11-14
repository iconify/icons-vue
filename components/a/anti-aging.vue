<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ysm9bsenp"/><path class="m-mw5tbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anti-aging" /></template>
<style>
.m-mw5tbwd {
  d: path("M19.5 13.5L18 15l1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysm9bsenp {
  d: path("M19.456 9.65C19.055 5.824 15.962 3 12 3C8 3 5 5.75 5 9.75l-1.5 3.5c-.25.5.1 1 .75 1H5v2.25c0 1.1.9 2 2 2h2v3m6-3.5a3 3 0 1 0 3-3");
}

</style>
