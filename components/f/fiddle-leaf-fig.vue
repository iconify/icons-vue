<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpskcyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fiddle-leaf-fig" /></template>
<style>
.kpskcyb5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 18h9l-1 3.5h-7Zm4.5 0V8m0 7.5c-1.5 0-2.5-.75-3.25-.75c-2 .25-4.25-1-4.25-3c0-1.75 2-2 3.5-1.25c1.25.75 1.5 2.5 4 5m0-4c1.5 0 2.5-.75 3.25-.75c2 .25 4.25-1 4.25-3c0-1.75-2-2-3.5-1.25c-1.25.75-1.5 2.5-4 5M12 8c-1.5-.5-2.75-1.5-2.75-3s.75-2.5 2-2.5s2 1 1.75 2.5s-.5 2-1 3");
}

</style>
