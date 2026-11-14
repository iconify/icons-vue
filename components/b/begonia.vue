<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owpugbxhf"/><path class="moxl-pt9w"/><path class="cbuak9bmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:begonia" /></template>
<style>
.cbuak9bmw {
  d: path("M12 18.5c1.5-3 6-3.5 8-2.5c-1 3-5 4-8 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moxl-pt9w {
  fill: currentColor;
  d: path("M12 9h.01");
}

.owpugbxhf {
  d: path("M12 9C8.5 4.5 3 5.5 3 9s5.5 4.5 9 0m0 0c3.5-4.5 9-3.5 9 0s-5.5 4.5-9 0m0 0c-1.75-2-1.5-5.5 0-6.5c1.5 1 1.75 4.5 0 6.5m0 0c-1.25 1.5-1 4 0 5c1-1 1.25-3.5 0-5m0 5v7.5");
}

</style>
