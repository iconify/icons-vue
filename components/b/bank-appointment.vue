<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h3zwapb2i"/><path class="ryj4tqwsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-appointment" /></template>
<style>
.h3zwapb2i {
  d: path("M7 4.5h10A3.5 3.5 0 0 1 20.5 8v10a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V8A3.5 3.5 0 0 1 7 4.5m1-2V6m8-3.5V6M3.5 8h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ryj4tqwsw {
  d: path("M10 12.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M7 21.5c0-2.5 2.25-4 5-4s5 1.5 5 4");
}

</style>
