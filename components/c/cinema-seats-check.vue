<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irkg7-bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-seats-check" /></template>
<style>
.irkg7-bdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H8v15H3.5Zm7.8 15H8v-5h10v2.3M8 9h7.5M11 17.5v.3m0 .4V21m-3 0h5m1.75-3l2 2L21 15.75");
}

</style>
