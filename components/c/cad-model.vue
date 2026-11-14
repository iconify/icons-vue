<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_3_fcchr"/><path class="warp9sian"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cad-model" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_3_fcchr {
  d: path("M12 2.5L20 7v10l-8 4.5L4 17V7Z");
}

.warp9sian {
  d: path("m4 7l4 2.25L12 7l4 2.25L20 7M8 9.25v5l4 2.25l4-2.25v-5m-4 7.25v5M12 7v5l-4 2.25M12 12l4 2.25");
}

</style>
