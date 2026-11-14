<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dgvfjop8a"/><path class="b-5izzb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-loyalty-card" /></template>
<style>
.b-5izzb1h {
  d: path("M4.75 14.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.dgvfjop8a {
  d: path("M2.5 5h19v14h-19Zm0 4h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
