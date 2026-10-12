<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hlaq-qpbp"/><path class="f5tfvfygz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gyroscope" /></template>
<style>
.f5tfvfygz {
  d: path("M7.25 11a4.75 1.75 0 1 0 9.5 0a4.75 1.75 0 1 0-9.5 0M12 2.75V18m.32.38l2.11 2.49q.32.38-.18.38h-4.5q-.5 0-.18-.38l2.11-2.49q.32-.38.64 0");
}

.hlaq-qpbp {
  d: path("M12 4a7 7 0 1 1 0 14a7 7 0 1 1 0-14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
