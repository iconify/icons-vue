<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuroep7vz"/><path class="kv5ylacwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-error" /></template>
<style>
.kv5ylacwr {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M15 15l6 6m0-6l-6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuroep7vz {
  d: path("M3.5 3v17.5h8.1");
}

</style>
