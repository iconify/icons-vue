<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o72p0hsyz"/><path class="s97n4nb-h"/><path class="hqoi59sxr"/><path class="z9nuhdbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-understand-outline-bold" /></template>
<style>
.hqoi59sxr {
  d: path("M12 9v7");
}

.o72p0hsyz {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s97n4nb-h {
  d: path("M8 11v5");
}

.z9nuhdbuz {
  d: path("M16 13v3");
}

</style>
