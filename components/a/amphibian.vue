<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oc2u4ccxz"/><path class="teq--xbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amphibian" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oc2u4ccxz {
  d: path("M4.5 9.5a3 3 0 1 1 5 0h5a3 3 0 1 1 5 0c2 1.5 2.25 5.5 0 7.5c-3 2.75-12 2.75-15 0c-2.25-2-2-6 0-7.5M7 8h.01M17 8h.01");
}

.teq--xbwy {
  d: path("M7.5 14q4.5 2.5 9 0");
}

</style>
