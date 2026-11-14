<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="en0djobdx"/><path class="eboc3hbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-carousel" /></template>
<style>
.eboc3hbqs {
  d: path("M6.5 7V6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v5.5m-5 3.5l3 3l-3 3");
}

.en0djobdx {
  d: path("M15.6 18H2.5V7h15v5.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
