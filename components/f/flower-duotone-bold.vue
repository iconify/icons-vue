<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b1ejurbkn"/><path class="ius2joz5m"/><path class="yl_qjhkkj"/><path class="sau_nibrh"/><path class="ykmyh8b9g"/><path class="gssdzduao"/><path class="tu-7id0rh"/><path class="gl3o38_gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flower-duotone-bold" /></template>
<style>
.b1ejurbkn {
  fill: currentColor;
  d: path("M7.5 7a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.gssdzduao {
  d: path("M5 18c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.ius2joz5m {
  fill: currentColor;
  d: path("M5 18c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sau_nibrh {
  d: path("M7.5 7a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.tu-7id0rh {
  d: path("M13 18c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.ykmyh8b9g {
  d: path("M12 11.5V21");
}

.yl_qjhkkj {
  fill: currentColor;
  d: path("M13 18c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
