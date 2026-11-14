<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8tw6fbis"/><path class="pjd6rdtmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:litmus-red" /></template>
<style>
.e8tw6fbis {
  d: path("M3.5 12h2v7A2.5 2.5 0 0 0 8 21.5h8a2.5 2.5 0 0 0 2.5-2.5v-7h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pjd6rdtmw {
  fill: currentColor;
  d: path("m14.526 2.713l.978.208A1.5 1.5 0 0 1 16.659 4.7L14.06 16.927a1.5 1.5 0 0 1-1.779 1.155l-.978-.208a1.5 1.5 0 0 1-1.155-1.779l2.599-12.227a1.5 1.5 0 0 1 1.779-1.155");
}

</style>
