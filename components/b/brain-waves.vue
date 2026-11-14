<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qk6uhsp0p"/><path class="a6lfsmb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brain-waves" /></template>
<style>
.a6lfsmb6t {
  d: path("M5.5 10.5h2l1.5-3l2 6L12.5 9l1 1.5H16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qk6uhsp0p {
  d: path("M6 21.5V17c-2.5-2-3.5-4.5-3.5-7c0-4.5 4-7.5 9-7.5c4.5 0 7.5 3 7.5 7l2 3.5h-2v3a1.5 1.5 0 0 1-1.5 1.5H15v4");
}

</style>
