<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="otw6d4bhw"/><path class="izthfd66a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:angler-reeling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izthfd66a {
  d: path("M6.25 17a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M20 3v12M9.5 17h.01");
}

.otw6d4bhw {
  d: path("M3.5 21Q10 9 20 3");
}

</style>
