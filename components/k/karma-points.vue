<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="wvy8edbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:karma-points" /></template>
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

.wvy8edbhr {
  d: path("m12.47 7.02l3.56 3.96q.47.52-.23.52h-1.1q-.7 0-.7.7v4.1q0 .7-.7.7h-2.6q-.7 0-.7-.7v-4.1q0-.7-.7-.7H8.2q-.7 0-.23-.52l3.56-3.96q.47-.52.94 0");
}

</style>
