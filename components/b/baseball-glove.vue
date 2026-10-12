<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tw1sp5bsm"/><circle class="zgdxchwpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baseball-glove" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tw1sp5bsm {
  d: path("M8.5 21.25v-13a5.5 5.5 0 0 1 11 0v11.5a1.5 1.5 0 0 1-1.5 1.5ZM12.25 5.5v3.75m3.5-3.75v3.75m-7.25 9h11M8.5 16l-4.1-5.35a1.75 1.75 0 0 1 2.7-2.2L8.5 10");
}

.zgdxchwpj {
  cx: 14px;
  cy: 13.25px;
  r: 2px;
}

</style>
