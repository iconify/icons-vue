<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wdd_k9f2l"/><path class="xx870zjbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glass-recycle-sharp" /></template>
<style>
.wdd_k9f2l {
  d: path("M16.5 4.21a9 9 0 1 1-9 0m-.65 2.42l.65-2.42l-2.42-.65");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xx870zjbv {
  d: path("M11 6.5h2V9l2.25.9V18h-6.5V9.9L11 9Z");
}

</style>
