<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="z7gs868um"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-tired" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7gs868um {
  d: path("M7.5 8.5L10 10l-2.5 1.5m9-3L14 10l2.5 1.5M9 17c0-1.75 1.35-3 3-3s3 1.25 3 3c0 .55-.45 1-1 1h-4c-.55 0-1-.45-1-1");
}

</style>
