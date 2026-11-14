<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ay_41p81m"/><path class="s21s-ccox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ink-cartridge" /></template>
<style>
.ay_41p81m {
  d: path("M7.625 2.5h8.75A2.625 2.625 0 0 1 19 5.125v11.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 16.875V5.125A2.625 2.625 0 0 1 7.625 2.5M10 19.5v2h4v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s21s-ccox {
  d: path("M12 7.5s3 3.5 3 5.5a3 3 0 0 1-6 0c0-2 3-5.5 3-5.5");
}

</style>
