<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubf_xjbni"/><path class="n-n33r6ou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-model" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-n33r6ou {
  d: path("m13.5 16.75l-2.75 2l2.75 2");
}

.ubf_xjbni {
  d: path("M4.25 2.5h4.5a1.75 1.75 0 0 1 1.75 1.75v4A1.75 1.75 0 0 1 8.75 10h-4.5A1.75 1.75 0 0 1 2.5 8.25v-4A1.75 1.75 0 0 1 4.25 2.5m11 10h4.5a1.75 1.75 0 0 1 1.75 1.75v5.5a1.75 1.75 0 0 1-1.75 1.75h-4.5a1.75 1.75 0 0 1-1.75-1.75v-5.5a1.75 1.75 0 0 1 1.75-1.75M2.5 5.5h8m3 9.75h8M6.5 10v8.75h7");
}

</style>
