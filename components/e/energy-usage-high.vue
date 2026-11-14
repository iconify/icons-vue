<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ftilk0z4c"/><path class="ti802mbws"/><path class="qawz0cb-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-usage-high" /></template>
<style>
.ftilk0z4c {
  d: path("M12.5 18.4v3.1h-8v-19h8v14.1");
}

.qawz0cb-i {
  d: path("M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.ti802mbws {
  fill: currentColor;
  d: path("M7.25 6h2.5v12.75h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
