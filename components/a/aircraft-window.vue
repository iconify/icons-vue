<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k95d55ntx"/><path class="j680cdc7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-window" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j680cdc7i {
  d: path("M8.5 15H15a2 2 0 0 0-.5-3.75a2.75 2.75 0 0 0-5.25.5A1.75 1.75 0 0 0 8.5 15");
}

.k95d55ntx {
  d: path("M12 2.5za7 7 0 0 1 7 7v5a7 7 0 0 1-7 7a7 7 0 0 1-7-7v-5a7 7 0 0 1 7-7");
}

</style>
