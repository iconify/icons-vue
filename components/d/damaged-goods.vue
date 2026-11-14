<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="saembjics"/><path class="bp3--9bvi"/><path class="u7ejlmt3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:damaged-goods" /></template>
<style>
.bp3--9bvi {
  d: path("M4 8h10a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V9.5A1.5 1.5 0 0 1 4 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.saembjics {
  d: path("m5.5 6l1.677-1.118A5.25 5.25 0 0 1 10.09 4h7.804a1.092 1.092 0 0 1 .606 2l-1.677 1.118A5.25 5.25 0 0 1 13.91 8H6.106A1.092 1.092 0 0 1 5.5 6");
}

.u7ejlmt3x {
  d: path("M17.838 6.441L18.5 6a1.93 1.93 0 0 1 3 1.606v7.084a5.25 5.25 0 0 1-2.338 4.369l-.662.441a1.93 1.93 0 0 1-3-1.606V10.81a5.25 5.25 0 0 1 2.338-4.369M9.5 8l-2 3.5l3 2.5L8 17.5l1 4M12 6h6");
}

</style>
