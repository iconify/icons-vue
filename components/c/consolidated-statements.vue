<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pm1fwcczn"/><path class="pf8ez5bvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consolidated-statements" /></template>
<style>
.pf8ez5bvy {
  d: path("M8 6V5a2.5 2.5 0 0 1 2.5-2.5h7A2.5 2.5 0 0 1 20 5v10.5a2.5 2.5 0 0 1-2.5 2.5h-1m-9 0v-3m3 3v-5.5m3 5.5V9.5");
}

.pm1fwcczn {
  d: path("M4.5 6h12v15.5h-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
