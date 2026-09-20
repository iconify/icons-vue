<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x_lkvk_2h"/><path class="ebuv7_btt"/><path class="dw_jcza0t"/><path class="ke-l5acyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-forward-outline-bold" /></template>
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x_lkvk_2h {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
