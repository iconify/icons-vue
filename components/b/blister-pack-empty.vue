<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjclid_jg"/><path class="a5d5__cgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blister-pack-empty" /></template>
<style>
.a5d5__cgm {
  d: path("M6 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7.5.5A2.25 2.25 0 1 0 18 9a2.25 2.25 0 1 0-4.5 0m-5.25 4.25a2.25 2.25 0 0 1 0 4.5m7.5-4.5a2.25 2.25 0 0 1 0 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjclid_jg {
  d: path("M5.5 2.5H17L20.5 6v13.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2");
}

</style>
