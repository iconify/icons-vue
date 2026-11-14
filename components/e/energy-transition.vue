<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="abi02fbuk"/><path class="q5xyx5bnm"/><path class="b31t3t6kn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-transition" /></template>
<style>
.abi02fbuk {
  d: path("M15.75 5.505A7.5 7.5 0 0 1 12 19.5");
}

.b31t3t6kn {
  d: path("m10 2.5l2 2l-2 2m2.75.75l-4.5 5.5h3.5l-.5 4l4.5-5.5h-3.5Z");
}

.q5xyx5bnm {
  d: path("m14 17.5l-2 2l2 2m-5.75-3.005A7.5 7.5 0 0 1 12 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
