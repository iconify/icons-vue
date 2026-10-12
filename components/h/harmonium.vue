<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gbgo_5bgz"/><rect class="jkggtjskl"/><path class="s2sj81x6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harmonium" /></template>
<style>
.gbgo_5bgz {
  d: path("M4.35 11.5h15.3q.6 0 .28-.51l-.61-.98q-.32-.51 0-1.02l.61-.98q.32-.51.05-1.05l-.71-1.42Q19 5 18.4 5H5.6q-.6 0-.87.54l-.71 1.42q-.27.54.05 1.05l.61.98q.32.51 0 1.02l-.61.98q-.32.51.28.51m1.15-4h13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkggtjskl {
  width: 18.5px;
  height: 9.75px;
  x: 2.75px;
  y: 11.5px;
  rx: 1.5px;
}

.s2sj81x6v {
  d: path("M5.25 15h13.5v3.5H5.25Zm4.5 0v3.5m4.5-3.5v3.5");
}

</style>
