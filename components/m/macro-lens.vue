<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="egzmyky0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:macro-lens" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.egzmyky0o {
  d: path("m9.32 7.99l.61.52q.57.49 1.02-.11l.6-.8q.45-.6.9 0l.6.8q.45.6 1.02.11l.61-.52q.57-.49.57.26v2.5q0 .75-.59 1.21l-2.07 1.58q-.59.46-1.18 0l-2.07-1.58q-.59-.46-.59-1.21v-2.5q0-.75.57-.26M12 14v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
