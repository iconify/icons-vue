<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bczv-ub-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infra-destroy" /></template>
<style>
.bczv-ub-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.4 13H2.5V3.5h17v9.2m-13-4.45h.01m3.49 0h5.5m0 8.75h6m-5 0v4.75h4V17m-3.25-1.5h2.5");
}

</style>
