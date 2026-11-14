<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="crinmcbgj"/><path class="cm-h74b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dust-mask-kit" /></template>
<style>
.cm-h74b3x {
  d: path("M4 6.25c-2 0-2 4.5.25 5.25M17 6.25c2.5 0 2.5 4.5-.25 5.25M18 15v6m-3-3h6");
}

.crinmcbgj {
  d: path("M12.19 15.548a7 7 0 0 1-1.69.202c-3.5 0-6.5-2.5-6.5-6.5v-4c3-1.5 10-1.5 13 0v4c0 1.113-.232 2.111-.644 2.97m-1.149 1.638a6.2 6.2 0 0 1-2.075 1.383");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
