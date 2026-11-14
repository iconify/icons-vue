<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ix_0itb3y"/><path class="lus0srido"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flat-roof-parapet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ix_0itb3y {
  d: path("M4.5 21.5v-18h15v18m-17 0h19m-17-14h15");
}

.lus0srido {
  d: path("M10 21.5V15h4v6.5");
}

</style>
