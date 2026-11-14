<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ev8l0ej4e"/><path class="puess-brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cover-limit-gauge" /></template>
<style>
.ev8l0ej4e {
  d: path("M3.773 19.25a9.5 9.5 0 1 1 16.454 0M12 14.5l4-4.5");
}

.puess-brb {
  d: path("M10.5 14.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12 6v1.5M5.25 10l1.25 1m12.25-1l-1.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
