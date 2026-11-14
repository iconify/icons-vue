<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_trv01ls"/><path class="en82bxb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-box" /></template>
<style>
.en82bxb_w {
  d: path("M12 13L7.75 8.75A2.75 2.75 0 0 1 12 5.25a2.75 2.75 0 0 1 4.25 3.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_trv01ls {
  d: path("M4.5 10v9A1.5 1.5 0 0 0 6 20.5h12a1.5 1.5 0 0 0 1.5-1.5v-9m-15 0l-2-3m17 3l2-3");
}

</style>
