<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lz2v-bc6z"/><path class="y19kd3bvu"/><rect class="tdty-0blt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bill-of-lading" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lz2v-bc6z {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 1.5px;
}

.tdty-0blt {
  width: 5.5px;
  height: 3px;
  x: 9.25px;
  y: 12.5px;
  rx: 0.5px;
}

.y19kd3bvu {
  d: path("M7.5 6.25h9m-9 3h6M7.25 15.5h9.5q.5 0 .28.45l-1.06 2.1q-.22.45-.72.45h-6.5q-.5 0-.72-.45l-1.06-2.1q-.22-.45.28-.45");
}

</style>
