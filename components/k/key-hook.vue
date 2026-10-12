<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z4wm0vbzx"/><path class="jnvuffqom"/><circle class="ywy4wr1fj"/><path class="de5zswlgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-hook" /></template>
<style>
.de5zswlgq {
  d: path("M16 15.75v5.5h1.5m-1.5-2.5h1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnvuffqom {
  d: path("M8 8.25v3.5a1.5 1.5 0 0 0 3 0v-.5m5-3v2.5");
}

.ywy4wr1fj {
  cx: 16px;
  cy: 13.25px;
  r: 2.5px;
}

.z4wm0vbzx {
  width: 16.5px;
  height: 4px;
  x: 3.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
