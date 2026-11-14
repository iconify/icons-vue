<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sh8rh7bsk"/><path class="kyds73bje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-cave" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kyds73bje {
  d: path("M8 18.5V14a4 4 0 0 1 8 0v4.5");
}

.sh8rh7bsk {
  d: path("M3.5 18.5c0-10 3-15 8.5-15s8.5 5 8.5 15M4 18.5h16a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20A1.5 1.5 0 0 1 4 18.5");
}

</style>
