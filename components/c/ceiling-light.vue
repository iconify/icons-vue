<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="txuf6ibwi"/><path class="c2dbjydhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ceiling-light" /></template>
<style>
.c2dbjydhq {
  d: path("M12 12.5a2.5 2.5 0 0 1 0 5m-5 1L5.5 20M17 18.5l1.5 1.5");
}

.txuf6ibwi {
  d: path("M12 2.5V7m-7 8c0-5 3-8 7-8s7 3 7 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
