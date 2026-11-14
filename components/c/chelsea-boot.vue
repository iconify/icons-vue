<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ffou5dbjx"/><path class="kksvvuvhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chelsea-boot" /></template>
<style>
.ffou5dbjx {
  d: path("M4 2.5h2.5v2H14V11c0 1.5 1 2.25 2.5 2.75l1.75.5a2.5 2.5 0 0 1 1.75 2.5v3.75H4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kksvvuvhd {
  d: path("M9 4.5v5a1.5 1.5 0 0 0 3 0v-5M4 17.75h16");
}

</style>
