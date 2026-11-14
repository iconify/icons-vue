<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l087an1gy"/><path class="c-b-2cbtp"/><path class="puizye_bx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clinic" /></template>
<style>
.c-b-2cbtp {
  d: path("M5 9v10.5c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V9");
}

.l087an1gy {
  d: path("M2.5 11L12 3l9.5 8");
}

.puizye_bx {
  d: path("M9 21.5V14h6v7.5m-3-6V19m-1.75-1.75h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
