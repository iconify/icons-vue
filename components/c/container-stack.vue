<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d84qmtbgz"/><path class="mijbvibik"/><rect class="hr74dlbru"/><path class="mjcmzysvq"/><rect class="s0l58-izb"/><path class="mz348jb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:container-stack" /></template>
<style>
.d84qmtbgz {
  width: 8px;
  height: 7px;
  x: 2.75px;
  y: 14.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr74dlbru {
  width: 8px;
  height: 7px;
  x: 13.25px;
  y: 14.25px;
  rx: 1px;
}

.mijbvibik {
  d: path("M5.5 16.75v2m2.5-2v2");
}

.mjcmzysvq {
  d: path("M16 16.75v2m2.5-2v2");
}

.mz348jb2q {
  d: path("M10.5 6.75v2.5m3-2.5v2.5");
}

.s0l58-izb {
  width: 9px;
  height: 7.5px;
  x: 7.5px;
  y: 4.25px;
  rx: 1px;
}

</style>
