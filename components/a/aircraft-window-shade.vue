<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k95d55ntx"/><path class="rfb-onlke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-window-shade" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k95d55ntx {
  d: path("M12 2.5za7 7 0 0 1 7 7v5a7 7 0 0 1-7 7a7 7 0 0 1-7-7v-5a7 7 0 0 1 7-7");
}

.rfb-onlke {
  d: path("M12 5.5za4 4 0 0 1 4 4v5a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-5a4 4 0 0 1 4-4M8 12h8m-5.5 2.75h3");
}

</style>
