<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v4b816bmf"/><path class="dw6q48mlo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flat-insurance" /></template>
<style>
.dw6q48mlo {
  d: path("M5.75 5.25H8.5V8H5.75Zm5.75 0h2.75V8H11.5Zm-5.75 5.5H8.5v2.75H5.75Zm5.75 0h2.75v2.75H11.5Zm7 4.25l3 1v2.5c0 1.75-1.5 2.75-3 3.25c-1.5-.5-3-1.5-3-3.25V16Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4b816bmf {
  d: path("M13.5 21.5H3v-19h14v10.1");
}

</style>
