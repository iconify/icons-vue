<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l3yek674e"/><path class="jsh68ybbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-attack" /></template>
<style>
.jsh68ybbr {
  fill: currentColor;
  d: path("M7.75 3.5L8 5.75l2.25.25L8.5 7.5l1 2.25l-2.25-1l-1.5 1.75l-.25-2.25L3.25 8L5 6.5L4 4.25l2.25 1Z");
}

.l3yek674e {
  d: path("M16.87 4.039A4.71 4.71 0 0 1 21 8.75C21 14.5 12 20 12 20s-3.6-2.2-6.246-5.271M13.5 9l-.671 1.342m.634 4.231L12.5 16.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
