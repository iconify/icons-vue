<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mt6pcobjc"/><path class="q1d1qljaw"/><path class="qk6s1kxhv"/><path class="ioeb-3q9w"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lollipop-chart-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ioeb-3q9w {
  d: path("M16 13v7");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.mt6pcobjc {
  d: path("M6 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.q1d1qljaw {
  d: path("M8 9v11");
}

.qk6s1kxhv {
  d: path("M14 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
