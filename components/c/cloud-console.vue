<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yhzh_gr8p"/><path class="iqxefnbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-console" /></template>
<style>
.iqxefnbub {
  d: path("M6 6.5L9 9l-3 2.5m4.5 0h3m3.5 7h3a2 2 0 0 0 0-4a2.75 2.75 0 0 0-5 .5a1.75 1.75 0 0 0 2 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhzh_gr8p {
  d: path("M11.4 15.5H2.5v-13h17v8.1M11 15.5V20m-3.5 0h5");
}

</style>
