<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhnxmhb1c"/><path class="t9jvgeb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemotherapy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhnxmhb1c {
  d: path("m12 9.5l1.5 2.25l2.75.75V15l1.5 2.5l-3.25.75l-1.5 2.5l-2.5-1.5l-3.25-.5l.75-3L7.25 13l2.25-1Z");
}

.t9jvgeb5w {
  fill: currentColor;
  d: path("M10.75 14c1-.75 2.75-.5 3 .75c.25 1.5-.5 2.5-2 2.25c-1.25 0-1.75-2.25-1-3M12 2.25C13.5 4 14.25 5 14.25 6c0 1.25-1 2-2.25 2s-2.25-.75-2.25-2c0-1 .75-2 2.25-3.75");
}

</style>
