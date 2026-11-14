<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oxs1q1bae"/><path class="d_hgu5bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hairpin-turn-right" /></template>
<style>
.d_hgu5bmn {
  d: path("m17 12.5l2.5 2.5l-2.5 2.5");
}

.oxs1q1bae {
  d: path("M4.5 20.5V7.75a4.25 4.25 0 0 1 8.5 0v3.75a3.5 3.5 0 0 0 3.5 3.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
