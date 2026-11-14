<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ocpzns7cq"/><path class="wbme2eb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aspect-ratio-16-9" /></template>
<style>
.ocpzns7cq {
  d: path("M2.5 6.75h19v10.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbme2eb2e {
  d: path("M5.75 12V9.75h2.5m10 2.25v2.25h-2.5");
}

</style>
