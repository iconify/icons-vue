<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw1o19ves"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cul-de-sac" /></template>
<style>
.pw1o19ves {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5v-7.75a6 6 0 1 1 6 0v7.75m-3-6v2m0 2v2M2.5 18l2.25-2L7 18v3.5H2.5V18M17 18l2.25-2l2.25 2v3.5H17V18");
}

</style>
