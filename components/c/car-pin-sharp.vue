<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vuz2t--mx"/><path class="h149zeb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-pin-sharp" /></template>
<style>
.h149zeb_v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 14.75h.01m8.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vuz2t--mx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5L5.6 7.1l.466-1.356L7.5 5.75h9l1.434-.006L18.4 7.1l1.85 5.4v5.75H3.75v-1Zm2.75 5.75v2.5m11-2.5v2.5m-13.25-9.5h15.5");
}

</style>
