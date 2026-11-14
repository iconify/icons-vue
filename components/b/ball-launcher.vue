<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jhq5n_qcf"/><path class="iukh-ybts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ball-launcher" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iukh-ybts {
  d: path("M6 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-3 2.5h11M16 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.jhq5n_qcf {
  d: path("m4.138 13.558l6.143-4.302a1.75 1.75 0 0 1 2.438.43l.573.819a1.75 1.75 0 0 1-.43 2.437l-6.143 4.302a1.75 1.75 0 0 1-2.438-.43l-.573-.819a1.75 1.75 0 0 1 .43-2.437");
}

</style>
