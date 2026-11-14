<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgtll7f9a"/><path class="u8054pfip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-cube" /></template>
<style>
.cgtll7f9a {
  d: path("m12 3l8.5 4.5v9L12 21l-8.5-4.5v-9Z");
}

.u8054pfip {
  d: path("M3.5 7.5L12 12l8.5-4.5M12 12v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
