<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="offs32jje"/><path class="wlfqnt68n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:factory-cloud" /></template>
<style>
.offs32jje {
  d: path("M11.18 19.5H2.5V8l5-4.5V8l5-4.5V8l5-4.5v9.42");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlfqnt68n {
  d: path("M6.5 19.5V15H10v4.5m6.75 1.5H20a1.75 1.75 0 0 0 .25-3.5a2.75 2.75 0 0 0-5.25.25A1.75 1.75 0 0 0 16.75 21Z");
}

</style>
