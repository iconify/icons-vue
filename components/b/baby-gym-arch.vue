<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_y_xq2lv"/><path class="il-50xbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-gym-arch" /></template>
<style>
.c_y_xq2lv {
  d: path("M2.5 21.5V12a9.5 9.5 0 0 1 19 0v9.5M8 3.5v5");
}

.il-50xbag {
  d: path("M5.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 3.5V9m-2.25 0h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
