<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fv_3r6but"/><path class="ld4r858hn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-cursing" /></template>
<style>
.fv_3r6but {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm4.25-4.25l3.5 1.5m7-1.5l-3.5 1.5M9 12h.01M15 12h.01");
}

.ld4r858hn {
  d: path("m7.5 17.5l2.25-2l2.25 2l2.25-2l2.25 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
