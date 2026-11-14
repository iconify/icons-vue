<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t9n3scb0u"/><path class="cx4fvlemb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:download" /></template>
<style>
.cx4fvlemb {
  d: path("M7.5 10.5L12 15l4.5-4.5");
}

.t9n3scb0u {
  d: path("M4 15v3a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-3M12 3.5V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
