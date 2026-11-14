<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0bq-nboz"/><path class="ln3modbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-schedule" /></template>
<style>
.ln3modbcl {
  d: path("M15.5 15h1.75l1 2.25l-1.25 1l2.25 2.25l1-1.25L22 20v1.75A6.75 6.75 0 0 1 15.5 15Z");
}

.q0bq-nboz {
  d: path("M14.4 20.5H3V4h17v10.4M8 2.5v3m7-3v3M3 9h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
