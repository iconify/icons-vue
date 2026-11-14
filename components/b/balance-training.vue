<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="stp1l5dou"/><path class="qq7dnpb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balance-training" /></template>
<style>
.qq7dnpb8e {
  d: path("M6 17.25a6 6 0 0 1 12 0Z");
}

.stp1l5dou {
  d: path("m2.692 10.7l18.096-3.846l.52 2.446l-18.096 3.846Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
