<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ga1oo1-xg"/><path class="o9cfn2b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lactation-support" /></template>
<style>
.ga1oo1-xg {
  d: path("M11.498 18.393a5.8 5.8 0 0 1-1.998.357c-3.25 0-6-2.75-6-6c0-3.5 3-6.5 6-10.25c2.63 3.288 5.26 5.999 5.869 8.976");
}

.o9cfn2b1f {
  d: path("M6.5 13c0 1.5 1 2.5 2.5 2.75m7-1.5h4c.95 0 1.75.8 1.75 1.75v2c0 .95-.8 1.75-1.75 1.75h-2.5l-2 1.75v-2c-.75-.25-1.25-.75-1.25-1.5v-2c0-.95.8-1.75 1.75-1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
