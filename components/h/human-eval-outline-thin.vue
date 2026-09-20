<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myekf3bzc"/><path class="cpvmwnddk"/><path class="zt8wecbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:human-eval-outline-thin" /></template>
<style>
.cpvmwnddk {
  d: path("M2 19a5 5 0 0 1 10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myekf3bzc {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.zt8wecbdr {
  d: path("m13 14 3 3 5 -5");
}

</style>
