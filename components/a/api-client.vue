<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jh049h-ll"/><path class="hesjb8b4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-client" /></template>
<style>
.hesjb8b4t {
  d: path("M13.5 6.25L11 8.75l2.5 2.5m3-5l2.5 2.5l-2.5 2.5M2.25 21.75c0-2 1.75-3.5 4-3.5s4 1.5 4 3.5m-7-9.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.jh049h-ll {
  d: path("M6.5 6.7V2.5h15.25V15H11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
