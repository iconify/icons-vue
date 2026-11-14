<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u-zi9ustu"/><path class="orfyzcc2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ev-charger-home" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.orfyzcc2p {
  d: path("M8.466 6.333L7.194 8.496a.5.5 0 0 0 .431.754a.696.696 0 0 1 .678.853l-.178.772a.235.235 0 0 0 .435.167l1.265-2.277A.515.515 0 0 0 9.375 8a.683.683 0 0 1-.663-.849l.163-.651a.223.223 0 0 0-.409-.167M8.5 15v2.25c0 4 9 4 9 0V15.5m-.75-5v-2m1.5 2v-2");
}

.u-zi9ustu {
  d: path("M6.125 2.5h4.75A2.625 2.625 0 0 1 13.5 5.125v7.25A2.625 2.625 0 0 1 10.875 15h-4.75A2.625 2.625 0 0 1 3.5 12.375v-7.25A2.625 2.625 0 0 1 6.125 2.5m11.125 8h.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-1.5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
