<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="g0zr_zwdg"/><path class="ktzvm-xej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cost-alert-outline-thin" /></template>
<style>
.g0zr_zwdg {
  d: path("M18 6v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ji-xh3b0v {
  d: path("M8 10.5v3");
}

.ktzvm-xej {
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lh7nxd5dq {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
