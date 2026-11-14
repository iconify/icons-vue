<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w2f3yh8lz"/><path class="n6thydbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antiseptic-bottle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6thydbzw {
  d: path("M12 12.25s2.75 2.75 2.75 4a2.75 2.75 0 0 1-5.5 0c0-1.25 2.75-4 2.75-4");
}

.w2f3yh8lz {
  d: path("m5 12.5l3.5-3h7l3.5 3V20a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20Zm5.75-9h2.5A1.75 1.75 0 0 1 15 5.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 7.75v-2.5a1.75 1.75 0 0 1 1.75-1.75M9 6h6");
}

</style>
