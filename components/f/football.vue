<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="ydu6uyzks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:football" /></template>
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

.ydu6uyzks {
  d: path("m12.61 8.94l2.11 1.54q.61.44.38 1.15l-.81 2.49q-.23.71-.98.71h-2.62q-.75 0-.98-.71l-.81-2.49q-.23-.71.38-1.15l2.11-1.54q.61-.44 1.22 0M12 6.75V4.5m4.99 5.88l2.14-.7m-4.04 6.57l1.32 1.82m-7.5-1.82l-1.32 1.82m-.58-7.69l-2.14-.7");
}

</style>
