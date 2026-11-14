<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8np3ob1n"/><path class="f6-k0ki0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chin-rest" /></template>
<style>
.f6-k0ki0a {
  d: path("M8.75 17.75a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0");
}

.g8np3ob1n {
  d: path("M12 6c3.5 0 5 1 5 3.25c0 1.75-2 2.25-2 4c0 1.5 3.5 1.75 3.5 4.75c0 2.5-3 3.5-6.5 3.5s-6.5-1-6.5-3.5c0-3 3.5-3.25 3.5-4.75c0-1.75-2-2.25-2-4C7 7 8.5 6 12 6m0-3.5V6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
