<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ah_9z7oja"/><path class="zah8ywbmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carer-allowance" /></template>
<style>
.ah_9z7oja {
  d: path("M11.9 16H2.5V4h18v9.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zah8ywbmw {
  d: path("M9 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8.5 11.25l-2.5-2.5a1.75 1.75 0 0 1 2.5-2.5a1.75 1.75 0 0 1 2.5 2.5Z");
}

</style>
