<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zey5ebc0a"/><path class="l8unaacgj"/><path class="m2zfyio4u"/><path class="s91z9mxxg"/><path class="uqi2guhey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breathe-in-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8unaacgj {
  d: path("M2 12h5");
}

.m2zfyio4u {
  d: path("m5 10 2 2 -2 2");
}

.s91z9mxxg {
  d: path("M22 12h-5");
}

.uqi2guhey {
  d: path("m19 10 -2 2 2 2");
}

.zey5ebc0a {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
