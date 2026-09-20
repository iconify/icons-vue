<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skbifdbcx"/><path class="i3qzahbyw"/><path class="wtfq6b2ta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-market-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3qzahbyw {
  d: path("M11 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.wtfq6b2ta {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
