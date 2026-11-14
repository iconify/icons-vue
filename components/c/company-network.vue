<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8w3c1u6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-network" /></template>
<style>
.g8w3c1u6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 20.5v-16A1.5 1.5 0 0 1 10.5 3h3A1.5 1.5 0 0 1 15 4.5v16m-11 0V12a1 1 0 0 1 1-1h4m6 0h4a1 1 0 0 1 1 1v8.5m-17.5 0h19M12 6.5v1m0 3v1m0 3v1m-5.5 0h.01m10.99 0h.01");
}

</style>
