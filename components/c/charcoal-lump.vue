<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ogzashxxm"/><path class="kry71abgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charcoal-lump" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kry71abgk {
  d: path("m5.5 8l5 4.5l3.5 8m1.5-9l2-6");
}

.ogzashxxm {
  d: path("m3.263 13.817l2.055-5.344a1.5 1.5 0 0 1 .614-.739l5.514-3.393a1.5 1.5 0 0 1 1.181-.17l4.252 1.16a1.5 1.5 0 0 1 .926.736l2.939 5.457a1.5 1.5 0 0 1 .15 1.006l-.762 3.808a1.5 1.5 0 0 1-.715 1.002l-4.979 2.904a1.5 1.5 0 0 1-.942.193l-6.771-.846a1.5 1.5 0 0 1-1.101-.717l-2.248-3.747a1.5 1.5 0 0 1-.113-1.31");
}

</style>
