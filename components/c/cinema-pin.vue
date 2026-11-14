<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mb1kdyqfx"/><path class="z682cpbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-pin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mb1kdyqfx {
  d: path("M12 21.5s7-6.5 7-12a7 7 0 0 0-14 0c0 5.5 7 12 7 12");
}

.z682cpbup {
  d: path("m12.055 7.467l1.206.768a1.5 1.5 0 0 1 0 2.53l-1.206.768a1.5 1.5 0 0 1-2.305-1.266V8.733a1.5 1.5 0 0 1 2.305-1.266");
}

</style>
