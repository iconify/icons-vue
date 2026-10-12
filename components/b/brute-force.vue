<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sz99y24cu"/><path class="hi_wydbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brute-force" /></template>
<style>
.hi_wydbqt {
  d: path("M5.25 11.75V9.5a3 3 0 0 1 6 0v2.25m-3 3.5v2.5m9.13-11.81l3.18 3.18q.53.53 0 1.06l-.88.88q-.53.53-1.06 0l-3.18-3.18q-.53-.53 0-1.06l.88-.88q.53-.53 1.06 0m-.07 3.25L12 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sz99y24cu {
  width: 11px;
  height: 9.5px;
  x: 2.75px;
  y: 11.75px;
  rx: 2px;
}

</style>
