<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rq88v3bnp"/><path class="n4_dx8isk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-queue-skip" /></template>
<style>
.n4_dx8isk {
  d: path("M18.5 13.75L21 16l.75-3.25M6 19.5h.01m5.99 0h.01m5.99 0h.01");
}

.rq88v3bnp {
  d: path("M3 16C4.5 5.5 19.5 5.5 21 16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
