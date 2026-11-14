<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sijnwbbdx"/><path class="wsdg-rb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capacity-factor" /></template>
<style>
.sijnwbbdx {
  d: path("M5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2.5-8l-11 10M3 16.5h18V21H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsdg-rb5h {
  fill: currentColor;
  d: path("M3 16.5h12.5V21H3Z");
}

</style>
