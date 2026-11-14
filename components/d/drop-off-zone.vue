<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="picfep-5o"/><path class="x9w7ry5vc"/><path class="xsx31p2rb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drop-off-zone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.picfep-5o {
  d: path("M2.5 17.5v-3l2.5-3h6l2.5 3h2.25v3Z");
}

.x9w7ry5vc {
  d: path("M4 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.xsx31p2rb {
  d: path("M2.5 21.5h16V18h3M9 2.5v6.25m-3-3l3 3l3-3");
}

</style>
