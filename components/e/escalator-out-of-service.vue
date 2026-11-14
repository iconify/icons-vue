<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8_jkmaeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:escalator-out-of-service" /></template>
<style>
.p8_jkmaeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20h4v-4h4v-1.1m4-3.8V8h5M3 15.5l4.243-4.243m3.959-3.959L14.5 4m-11-.5l17 17");
}

</style>
