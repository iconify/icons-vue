<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zi_car8rs"/><path class="az9qzud3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-overdrawn" /></template>
<style>
.az9qzud3f {
  d: path("M10.5 3.5h3a8.5 8.5 0 0 1 0 17h-3M7 12h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zi_car8rs {
  d: path("M2 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

</style>
