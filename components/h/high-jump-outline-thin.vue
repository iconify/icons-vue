<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m1mjigbsi"/><path class="ml3aqbbkk"/><path class="t1tm72bkp"/><path class="zyvg9rbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:high-jump-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1mjigbsi {
  d: path("M4 8h16");
}

.ml3aqbbkk {
  d: path("M4 8v12");
}

.t1tm72bkp {
  d: path("M20 8v12");
}

.zyvg9rbxb {
  d: path("M6 15c2 -7 10 -7 12 0");
}

</style>
