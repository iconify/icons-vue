<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rq_h61bzk"/><path clip-rule="evenodd" class="nbjsuy_7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyboard-off-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nbjsuy_7f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 7L15 7L15 9L13 9L13 7ZM17 7L19 7L19 9L17 9L17 7ZM5 11L7 11L7 13L5 13L5 11ZM17 11L19 11L19 13L17 13L17 11Z");
  stroke: none;
}

.rq_h61bzk {
  d: path("M20 20L2 20L2 4L4 4M7 16L16 16M8.6569 4L22 4L22 17.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
