<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="atj48gb0n"/><path class="yktp97b4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biomass-boiler" /></template>
<style>
.atj48gb0n {
  d: path("M13.5 6.5h8v15h-8Zm4 0V3m-2 0h4m-17 6l1 8.5h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yktp97b4h {
  d: path("M5.5 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
