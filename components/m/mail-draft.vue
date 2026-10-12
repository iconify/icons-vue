<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hhycw79tw"/><path class="iorq_lb7e"/><rect class="edrrvhbbp"/><path class="tvh6s4bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-draft" /></template>
<style>
.edrrvhbbp {
  width: 6.5px;
  height: 8px;
  x: 14.75px;
  y: 2.75px;
  rx: 1.25px;
}

.hhycw79tw {
  width: 14.5px;
  height: 12px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iorq_lb7e {
  d: path("m6 10.75l3.65 2.75c.8.6 1.9.6 2.7 0L16 10.75");
}

.tvh6s4bcg {
  d: path("M16.75 5.25h2.5m-2.5 2.5h1.5");
}

</style>
