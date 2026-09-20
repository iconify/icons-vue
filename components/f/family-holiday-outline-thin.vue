<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w51c2lb3g"/><path class="ie7ib2yuv"/><path class="o849aebzd"/><path class="luwyinzbc"/><path class="wa8tqsbro"/><path class="uqgjqlbyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-holiday-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie7ib2yuv {
  d: path("M2 20a4.5 4.5 0 0 1 9 0");
}

.luwyinzbc {
  d: path("M10 19a5 5 0 0 1 10 0");
}

.o849aebzd {
  d: path("M12 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.uqgjqlbyz {
  d: path("M17 20a2.5 2.5 0 0 1 5 0");
}

.w51c2lb3g {
  d: path("M3.5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wa8tqsbro {
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
