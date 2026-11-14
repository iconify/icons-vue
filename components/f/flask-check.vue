<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5k1-5ffr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flask-check" /></template>
<style>
.j5k1-5ffr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8m-6.5 0v6L3.75 20q-.5 1 .75 1h9.293m5.883-.005q.806-.054.706-.626m-2.611-5.326L14.5 8.5v-6M7.25 13h9.5m-2 5l2 2L21 15.75");
}

</style>
