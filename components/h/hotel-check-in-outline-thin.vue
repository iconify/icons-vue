<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q7l4tcb1c"/><path class="gsq10_ixg"/><path class="mu9c_kkxj"/><path class="nm65bwi7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hotel-check-in-outline-thin" /></template>
<style>
.gsq10_ixg {
  d: path("M7 6h4v3H7Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu9c_kkxj {
  d: path("M7 15h8");
}

.nm65bwi7e {
  d: path("M12.5 12.5 15 15l-2.5 2.5");
}

.q7l4tcb1c {
  d: path("M6 3h11l4 4v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2V5a2 2 0 0 1 2 -2");
}

</style>
