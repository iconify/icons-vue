<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3opjgvay"/><path class="qbgp8rbjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-sync" /></template>
<style>
.n3opjgvay {
  d: path("M4.5 12a7.6 7.6 0 0 1 13.25-5m1.75 5a7.6 7.6 0 0 1-13.25 5");
}

.qbgp8rbjl {
  d: path("M17.75 4v3h-3m-8.5 13v-3h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
