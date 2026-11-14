<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6mvw1bnp"/><path class="wwx6chb1k"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-inventory" /></template>
<style>
.h6mvw1bnp {
  d: path("M12.29 21.355L12 21.5L3 17V7l9-4.5L21 7v5.538");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwx6chb1k {
  d: path("m3 7l9 4.5L21 7m-9 4.5v3.6m0 5.8v.6M7.5 4.75l9 4.5M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
