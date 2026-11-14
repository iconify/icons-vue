<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f5i706bnm"/><path class="a7ybq_cpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:achievement-locked" /></template>
<style>
.a7ybq_cpq {
  d: path("M7 13.75v7.75l3-2l2.2 1.467m.8-6.306v-.911M7 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm8 9h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.f5i706bnm {
  d: path("M4 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
