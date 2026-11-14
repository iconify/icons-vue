<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pzk555bgy"/><path class="ar9130bks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liquidity-gauge" /></template>
<style>
.ar9130bks {
  d: path("M12 8.5s-3 3.25-3 5.25a3 3 0 0 0 6 0c0-2-3-5.25-3-5.25Z");
}

.pzk555bgy {
  d: path("M3.773 19.25a9.5 9.5 0 1 1 16.454 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
