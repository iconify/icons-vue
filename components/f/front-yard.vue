<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fg2cojb1o"/><path class="kibw1zuqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:front-yard" /></template>
<style>
.fg2cojb1o {
  d: path("m3.013 9.487l3.75-3.75a1.75 1.75 0 0 1 2.474 0l3.75 3.75a1.75 1.75 0 0 1 .513 1.238v9.025a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-9.025a1.75 1.75 0 0 1 .513-1.238M17.875 12.5h1.75a1.875 1.875 0 0 1 1.875 1.875a1.875 1.875 0 0 1-1.875 1.875h-1.75A1.875 1.875 0 0 1 16 14.375a1.875 1.875 0 0 1 1.875-1.875m.875 3.75v5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kibw1zuqs {
  d: path("M6.25 21.5v-5h3.5v5m10.5-9v-3H18.5v1.25h1.75");
}

</style>
