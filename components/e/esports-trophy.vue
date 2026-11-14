<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dlpogzboz"/><path class="cbdtpcbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:esports-trophy" /></template>
<style>
.cbdtpcbdh {
  d: path("M5 5.5H3V7a3 3 0 0 0 2.5 3M15 5.5h2V7a3 3 0 0 1-2.5 3M10 13v5m-2.25 0h4.5m4.5-3.5h3a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 19h-3A1.75 1.75 0 0 1 15 17.25v-1a1.75 1.75 0 0 1 1.75-1.75m1.5 4.5v2.5m-2 0h4");
}

.dlpogzboz {
  d: path("M5 3.5h10V8A5 5 0 0 1 5 8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
