<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tcnbl7bcm"/><path class="kh4k_3_sh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carp" /></template>
<style>
.kh4k_3_sh {
  d: path("M7.5 9.5C9 5.5 12 5 15 10.25M4.5 13l-2 3m3.25-.75l-.5 3.25m2.5-6h.01");
}

.tcnbl7bcm {
  d: path("M4.5 13c2.5-6 9.5-6 12 0L21 9v8l-4.5-4c-2.5 6-9.5 6-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
