<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tnsp6xb2l"/><path class="jhxad-bnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-review" /></template>
<style>
.jhxad-bnw {
  d: path("m12 6.5l1.176 2.382l2.628.382l-1.902 1.854l.449 2.618L12 12.5l-2.351 1.236l.449-2.618l-1.902-1.854l2.628-.382Z");
}

.tnsp6xb2l {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5v10a2.5 2.5 0 0 1-2.5 2.5H11l-4 3.5V18H5.5A2.5 2.5 0 0 1 3 15.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
