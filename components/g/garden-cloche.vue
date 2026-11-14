<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gksyehfcl"/><path class="kgpdbmadn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-cloche" /></template>
<style>
.gksyehfcl {
  d: path("M5 21v-9c0-4.5 3-7 7-7s7 2.5 7 7v9M3 21h18M12 5V3m0 18v-6");
}

.kgpdbmadn {
  d: path("M12 15c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0 0c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
