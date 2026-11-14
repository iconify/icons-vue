<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-85jv38c"/><path class="rstwyvbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-pipeline" /></template>
<style>
.p-85jv38c {
  d: path("M2.75 14H16.5V5m4 0v9a4 4 0 0 1-4 4H2.75m0-5.5v7M15.25 5h6.5M9 14v-3.25");
}

.rstwyvbjs {
  d: path("M6.25 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
