<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rgm5-92up"/><path class="es-8_jb_y"/><path class="q_xymip_v"/><path class="po47_2bjy"/><path class="oz614acod"/><path class="iqy6wdsji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dance-floor-duotone-bold" /></template>
<style>
.es-8_jb_y {
  fill: currentColor;
  d: path("M13 7h7v6h-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iqy6wdsji {
  d: path("M8 16h7v5H8Z");
}

.oz614acod {
  d: path("M13 7h7v6h-7Z");
}

.po47_2bjy {
  d: path("M3 7h7v6H3Z");
}

.q_xymip_v {
  fill: currentColor;
  d: path("M8 16h7v5H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rgm5-92up {
  fill: currentColor;
  d: path("M3 7h7v6H3Z");
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

</style>
