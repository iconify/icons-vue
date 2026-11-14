<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="omiizcsca"/><path class="alw06xnoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-mart" /></template>
<style>
.alw06xnoe {
  d: path("M7 13c0 1 2.2 2 5 2s5-1 5-2");
}

.omiizcsca {
  d: path("m3 7l1.5-4h15L21 7M7 13c0-1 2.2-2 5-2s5 1 5 2v6.5c0 1.1-2.2 2-5 2s-5-.9-5-2ZM3 7a2.25 2.25 0 0 0 4.5 0A2.25 2.25 0 0 0 12 7a2.25 2.25 0 0 0 4.5 0A2.25 2.25 0 0 0 21 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
