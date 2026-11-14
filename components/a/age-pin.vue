<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qf1g46b0o"/><path class="t466k4b2z"/><path class="q03zipf7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:age-pin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q03zipf7a {
  d: path("M12.75 17a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.qf1g46b0o {
  d: path("M7.5 9V7a4.5 4.5 0 0 1 9 0v2M7.375 9h9.25A4.375 4.375 0 0 1 21 13.375v3.75a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-3.75A4.375 4.375 0 0 1 7.375 9M9 11.75v7");
}

.t466k4b2z {
  d: path("M12.75 13.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
