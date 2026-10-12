<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmnyfnbre"/><circle class="cgeon5wki"/><path class="r0i38ebaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:depth-of-field" /></template>
<style>
.cgeon5wki {
  cx: 13.71px;
  cy: 10.29px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmnyfnbre {
  d: path("M11.5 16.5a4 4 0 1 1-8 0a4 4 0 1 1 8 0");
}

.r0i38ebaj {
  d: path("M20.5 5.5a2 2 0 1 1-4 0a2 2 0 1 1 4 0");
}

</style>
