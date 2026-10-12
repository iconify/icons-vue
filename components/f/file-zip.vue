<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="v4uxgbxyf"/><rect class="ow9ixg9ca"/><path class="hd32d7bne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-zip" /></template>
<style>
.hd32d7bne {
  d: path("M12 14.25v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz9wy2bsc {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

.ow9ixg9ca {
  width: 3px;
  height: 4.5px;
  x: 10.5px;
  y: 12.5px;
  rx: 1px;
}

.v4uxgbxyf {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5M11 4.75h1m1 1.5h-1m-1 1.5h1m1 1.5h-1m-1 1.5h1");
}

</style>
