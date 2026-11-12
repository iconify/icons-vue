<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><path class="tw30_ubet"/><path class="yic1xvbbc"/><path class="hhi9k4bqd"/><path class="s8xjouf5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-3-linear" /></template>
<style>
.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.hhi9k4bqd {
  d: path("M10 12.3115C10 7.31152 22 7.71152 22 15.3115");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s8xjouf5y {
  d: path("M14 12C14 17 2 16.6 2 9");
}

.tw30_ubet {
  d: path("M12 10C17 10 16.6 22 9 22");
}

.yic1xvbbc {
  d: path("M12.3115 14C7.31152 14 7.71152 2 15.3115 2");
}

</style>
