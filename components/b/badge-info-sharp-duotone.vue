<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g70whwsdk"/><path class="m8hyyfbac"/><path class="ff45hndep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-info-sharp-duotone" /></template>
<style>
.ff45hndep {
  fill: currentColor;
  d: path("M13 7C13 6.4477 12.5523 6 12 6C11.4477 6 11 6.4477 11 7C11 7.5523 11.4477 8 12 8C12.5523 8 13 7.5523 13 7Z");
  stroke: none;
}

.g70whwsdk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.3891 8.1109C22.4205 9.1424 23 10.5413 23 12C23 13.4587 22.4205 14.8576 21.3891 15.8891C21.3891 18.9267 18.9267 21.3891 15.8891 21.3891C14.8576 22.4205 13.4587 23 12 23C10.5413 23 9.1424 22.4205 8.1109 21.3891C5.0733 21.3891 2.6109 18.9267 2.6109 15.8891C1.5795 14.8576 1 13.4587 1 12C1 10.5413 1.5795 9.1424 2.6109 8.1109C2.6109 5.0733 5.0733 2.6109 8.1109 2.6109C9.1424 1.5795 10.5413 1 12 1C13.4587 1 14.8576 1.5795 15.8891 2.6109C18.9267 2.6109 21.3891 5.0733 21.3891 8.1109Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m8hyyfbac {
  d: path("M12 18L12 10");
}

</style>
