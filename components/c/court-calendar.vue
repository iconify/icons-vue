<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="woapewu-e"/><path class="s-3e9-k4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:court-calendar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-3e9-k4e {
  d: path("M8 2.75v3m8-3v3M2.75 9h18.5M7.93 13.49l3.64-2.23q.43-.26.86 0l3.64 2.23q.43.26-.07.26H8q-.5 0-.07-.26M9.25 15v2M12 15v2m2.75-2v2M7.5 18.25h9");
}

.woapewu-e {
  width: 18.5px;
  height: 17px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
