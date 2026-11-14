<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5bcdvbpf"/><path class="a--81zb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insurance-office" /></template>
<style>
.a--81zb-d {
  d: path("M7 13.25a5 5 0 0 1 10 0Zm5 0v3.5a1.5 1.5 0 0 1-3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5bcdvbpf {
  d: path("M3.5 10L12 3l8.5 7v11h-17Z");
}

</style>
