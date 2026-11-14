<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e32hkxxew"/><path class="w629tr23n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:device-donate" /></template>
<style>
.e32hkxxew {
  d: path("M14.6 21.5H4.5v-19h12v10.1M9 18h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w629tr23n {
  d: path("M18.25 21.25L15.5 18.5a2 2 0 0 1 2.75-2.75A2 2 0 0 1 21 18.5Z");
}

</style>
