<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q95wyyyjq"/><path class="t407ddc6o"/><path class="dcemxxfpc"/><path class="uv_v7wb2g"/><path class="zpl29uvhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:few-shot-outline-bold" /></template>
<style>
.dcemxxfpc {
  d: path("M3 19h8");
}

.q95wyyyjq {
  d: path("M3 5h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t407ddc6o {
  d: path("M3 12h8");
}

.uv_v7wb2g {
  d: path("M14 12h5");
}

.zpl29uvhf {
  d: path("m16 9 3 3 -3 3");
}

</style>
