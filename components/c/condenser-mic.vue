<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u3ch6wb0w"/><path class="ydcdj6b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:condenser-mic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u3ch6wb0w {
  width: 7.5px;
  height: 12px;
  x: 8.25px;
  y: 2.75px;
  rx: 3.75px;
}

.ydcdj6b6g {
  d: path("M8.25 7h7.5m-7.5 3.5h7.5m-7.5.5H5.5v6.75h13V11h-2.75M12 17.75v3.5m-3 0h6");
}

</style>
