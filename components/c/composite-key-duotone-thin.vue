<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkaxw8b5s"/><path class="m_m6c4t8g"/><path class="va0rjdbnq"/><path class="hcn7bdzwu"/><path class="dky0phbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:composite-key-duotone-thin" /></template>
<style>
.dky0phbxv {
  d: path("M19 11v7");
}

.hcn7bdzwu {
  d: path("M15 11v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkaxw8b5s {
  fill: currentColor;
  d: path("M2 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m_m6c4t8g {
  d: path("M2 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.va0rjdbnq {
  d: path("M8 11h12");
}

</style>
