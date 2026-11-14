<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-acqbcza"/><path class="bdguedbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:double-trailer" /></template>
<style>
.bdguedbcu {
  d: path("M3.5 16.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m5.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-acqbcza {
  d: path("M4.25 5.5h2A1.75 1.75 0 0 1 8 7.25v6A1.75 1.75 0 0 1 6.25 15h-2a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 4.25 5.5M8 13h2.75m1.75-7.5h2a1.75 1.75 0 0 1 1.75 1.75v6A1.75 1.75 0 0 1 14.5 15h-2a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 12.5 5.5M16.25 8H19l2.5 3v4h-5.25");
}

</style>
