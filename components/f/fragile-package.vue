<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pny41bcag"/><path class="gzcnkccgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fragile-package" /></template>
<style>
.gzcnkccgj {
  d: path("M12 8.5L10 12l3.5 3l-2.5 5.5");
}

.pny41bcag {
  d: path("M3 3.5h18v17H3Zm0 5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
