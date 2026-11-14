<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pcpwu3xaj"/><path class="dm3tsccui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brain-coral" /></template>
<style>
.dm3tsccui {
  d: path("M8 9.5c1.25-1.5 2.75 1.5 4 0s2.75 1.5 4 0m-9 5c1.25-1.5 2.25 1.5 3.5 0s2.25 1.5 3.5 0s2.25 1.5 3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcpwu3xaj {
  d: path("M2.5 19.5c0-10 4.5-16 9.5-16s9.5 6 9.5 16Z");
}

</style>
