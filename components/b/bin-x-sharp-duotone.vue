<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j1rhegwai"/><path class="qlqss_bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-x-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j1rhegwai {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6L19 6L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22Z");
  stroke: none;
}

.qlqss_bdw {
  d: path("M9 2L15 2M3 7L21 7M9.7071 12.7071L14.2929 17.2929M14.2929 12.7071L9.7071 17.2929");
}

</style>
