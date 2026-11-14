<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="drcd8sbrs"/><path class="j4b-4km1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esim-transfer" /></template>
<style>
.drcd8sbrs {
  d: path("M2.5 8.5h7v13h-7Zm12 0h7v13h-7ZM6 5.5c2-3 10-3 12 0");
}

.j4b-4km1x {
  d: path("m15.5 5l2.5.5l.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
