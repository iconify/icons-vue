<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3o9qbc7q"/><path class="t7edyg0pd"/><path class="uzfts2bhc"/><path class="qot4e3zhe"/><path class="lwy-ztd6t"/><path class="nie2ttb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:goal-drift-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwy-ztd6t {
  d: path("M3 5h11.5");
}

.nie2ttb8o {
  d: path("M14.5 2.5 17 5l-2.5 2.5");
}

.qot4e3zhe {
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.r3o9qbc7q {
  fill: currentColor;
  d: path("M4 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t7edyg0pd {
  fill: currentColor;
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uzfts2bhc {
  d: path("M4 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
