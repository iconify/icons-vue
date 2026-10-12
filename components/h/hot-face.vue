<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="eql4g5bvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-face" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.eql4g5bvz {
  d: path("M7 10.9c.6-.4 2.15-.4 2.75 0m4.5 0c.6-.4 2.15-.4 2.75 0m-7.25 2.95h4.5a2.25 2.25 0 0 1-4.5 0M12.6 5.8c.6.9.9 1.45.9 1.95a.9.9 0 0 1-1.8 0c0-.5.3-1.05.9-1.95");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
