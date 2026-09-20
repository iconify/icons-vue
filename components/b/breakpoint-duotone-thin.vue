<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wyj9kwb_b"/><path class="n7d250moc"/><path class="tee3b-ble"/><path class="jlpxneb5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breakpoint-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.n7d250moc {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.tee3b-ble {
  d: path("M10 12h11");
}

.wyj9kwb_b {
  fill: currentColor;
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
