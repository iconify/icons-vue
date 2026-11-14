<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sknp0l-1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disinfectant-spray" /></template>
<style>
.sknp0l-1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11h9v10H5Zm2 0V7a2 2 0 0 1 2-2h6v3h-3v3m-2.5 2.75v4.5M7.25 16h4.5m6.75-9.5h.01m2.49-2h.01m-.01 4h.01");
}

</style>
