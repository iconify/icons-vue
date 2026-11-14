<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0n8-nvma"/><path class="hwvbnxsim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donation-pickup" /></template>
<style>
.g0n8-nvma {
  d: path("M2.5 16.5V7A1.5 1.5 0 0 1 4 5.5h11l6.5 5.5v5.5Z");
}

.hwvbnxsim {
  d: path("M15 5.5V11h6.5M6 10.5V14h5.5v-3.5Zm0 0L4.75 8.25m6.75 2.25l1.25-2.25M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
