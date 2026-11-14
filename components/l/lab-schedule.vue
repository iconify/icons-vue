<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qo05omb1p"/><path class="q_5_1kbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-schedule" /></template>
<style>
.q_5_1kbkt {
  d: path("M6.5 10.5h11V14h-11Zm0 6.5h6");
}

.qo05omb1p {
  d: path("M3 4h18v17.5H3Zm5-1.5V6m8-3.5V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
