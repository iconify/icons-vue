<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="legud0bli"/><path class="zay-fdbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fireplace-surround" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.legud0bli {
  d: path("M2.5 4h19m-17 0v16.5M19.5 4v16.5m-17 0h19M8 20.5V12a4 4 0 0 1 8 0v8.5");
}

.zay-fdbbt {
  d: path("M12 12.25c1 1 1.5 2.5 1.5 4a1.5 1.5 0 0 1-3 0c0-1.5.5-3 1.5-4");
}

</style>
