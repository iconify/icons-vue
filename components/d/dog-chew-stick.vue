<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlmwnci7o"/><path class="kx063ib2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-chew-stick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx063ib2e {
  d: path("M3.697 17.303a3 3 0 1 0 6 0a3 3 0 1 0-6 0M14.303 6.697a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.tlmwnci7o {
  d: path("m8.818 13.061l4.243-4.243a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-4.243 4.243a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121");
}

</style>
