<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i66l-s0fe"/><path class="bkd9t9_ww"/><path class="uvgrx_yvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:birthday-reward-duotone-bold" /></template>
<style>
.bkd9t9_ww {
  d: path("M3 21v-7h4V8h10v6h4v7Z");
}

.i66l-s0fe {
  fill: currentColor;
  d: path("M3 21v-7h4V8h10v6h4v7Z");
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

.uvgrx_yvv {
  d: path("M12 3v5");
}

</style>
