<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n6p_w5bjg"/><path class="gqxll333e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-stack" /></template>
<style>
.gqxll333e {
  d: path("M2.75 9.25a2 2 0 0 1 2-2h3.5l2 2h6a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6p_w5bjg {
  d: path("M5.75 7.25v-2.5a2 2 0 0 1 2-2H11l2 2h6.25a2 2 0 0 1 2 2V18");
}

</style>
