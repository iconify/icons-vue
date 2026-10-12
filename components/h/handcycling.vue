<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zzw57zywt"/><path class="s74849u0h"/><circle class="mqm_6ebad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handcycling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqm_6ebad {
  cx: 6.25px;
  cy: 5px;
  r: 2px;
}

.s74849u0h {
  d: path("m6.75 17.25l3-5h4.5l4 6m-8.5-6l-2.25-4m.5 1l5.75 1.5l1.25 2.5");
}

.zzw57zywt {
  d: path("M2.75 17.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0m12.5 1a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
