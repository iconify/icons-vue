<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y2fv77euv"/><path class="u3s0k3jvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fibre-cabinet" /></template>
<style>
.u3s0k3jvy {
  fill: currentColor;
  d: path("M18.75 6.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2fv77euv {
  d: path("M3 2.5h12v16H3Zm6 0v16m-4 0V21m8-2.5V21m2-7h2a3 3 0 0 0 3-3v-.5");
}

</style>
