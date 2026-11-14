<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxrgubumk"/><path class="qq7dnpb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balance-training" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qq7dnpb8e {
  d: path("M6 17.25a6 6 0 0 1 12 0Z");
}

.sxrgubumk {
  d: path("m3.915 10.441l15.65-3.327a1.25 1.25 0 0 1 1.483.963a1.25 1.25 0 0 1-.963 1.482l-15.65 3.327a1.25 1.25 0 0 1-1.483-.963a1.25 1.25 0 0 1 .963-1.482");
}

</style>
