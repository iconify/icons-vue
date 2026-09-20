<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcy6xobcc"/><path class="snl1mwbpd"/><path class="lez94ab8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coin-collecting-outline-thin" /></template>
<style>
.gcy6xobcc {
  d: path("M3 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lez94ab8w {
  d: path("M15 6c3 1 5 3 5 6s-2 5 -5 6");
}

.snl1mwbpd {
  d: path("M7 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
