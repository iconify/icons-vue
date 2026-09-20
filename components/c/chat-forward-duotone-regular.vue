<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uojx2-ana"/><path class="x_lkvk_2h"/><path class="ebuv7_btt"/><path class="dw_jcza0t"/><path class="ke-l5acyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-forward-duotone-regular" /></template>
<style>
.dw_jcza0t {
  d: path("M7 10h8.5");
}

.ebuv7_btt {
  d: path("M7 17v3l3 -3");
}

.ke-l5acyt {
  d: path("m13 7.5 2.5 2.5 -2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uojx2-ana {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x_lkvk_2h {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
