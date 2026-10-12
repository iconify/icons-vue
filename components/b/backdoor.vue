<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hmgkmpsgr"/><path class="x1ii2sb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backdoor" /></template>
<style>
.hmgkmpsgr {
  width: 18.5px;
  height: 17.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1ii2sb5t {
  d: path("M2.75 8.5h18.5m-18.5 4.75H6.5m11 0h3.75M9 3.75V8.5m6-4.75V8.5M8.75 21.25v-5a3.25 3.25 0 0 1 6.5 0v5Z");
}

</style>
