<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="grri4hb6u"/><path class="js3aemb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dna-check" /></template>
<style>
.grri4hb6u {
  d: path("M4 2.5c0 4.75 9 5.25 9 9.5s-9 4.75-9 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.js3aemb2a {
  d: path("M13 2.5c0 4.75-9 5.25-9 9.5s9 4.75 9 9.5m-8.5-17h8M4 12h9m-8.5 7.5h7.9m2.35-1.5l2 2L21 15.75");
}

</style>
