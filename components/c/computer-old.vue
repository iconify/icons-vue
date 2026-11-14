<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6nuy14uw"/><path class="nbi6ewb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:computer-old" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbi6ewb5o {
  d: path("M8.25 6.5h3.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 11.75 11h-3.5A1.75 1.75 0 0 1 6.5 9.25v-1A1.75 1.75 0 0 1 8.25 6.5M14 18h4");
}

.v6nuy14uw {
  d: path("M7 3.5h10A3.5 3.5 0 0 1 20.5 7v3.5A3.5 3.5 0 0 1 17 14H7a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 7 3.5m-2 12h14a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 18A2.5 2.5 0 0 1 5 15.5");
}

</style>
