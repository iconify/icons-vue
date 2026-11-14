<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="euqe4vbff"/><path class="pos7keb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballot-box" /></template>
<style>
.euqe4vbff {
  d: path("M7 11.5h10a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-3A3.5 3.5 0 0 1 7 11.5m1 0v-8a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pos7keb4z {
  d: path("m10.25 7l1.25 1.25L13.75 6");
}

</style>
