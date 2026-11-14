<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ky431dr5k"/><path class="ujfsvl36y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ballot-envelope" /></template>
<style>
.ky431dr5k {
  d: path("M2.5 11h19v10.5h-19ZM6 11V2.5h12V11");
}

.ujfsvl36y {
  d: path("M2.75 12L12 17l9.25-5M9.75 6.25L11.5 8l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
